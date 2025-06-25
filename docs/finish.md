# Finishing touches

## Cleanup

Once you're ready to clean up your OpenShift project, follow the instructions in this section.

1. **Run the following command to clean up most of the objects in your project**. Remember to change the value of `NN`.

    ```text
    oc delete all --all -n userNN-project
    ```

    This will delete some of the objects in your project, but it will not delete the secret you created.

2. **Delete your secret with the following command**.

    ```text
    oc delete secret nationalparks-mongodb-parameters -n userNN-project
    ```

## Conclusion

To learn more about OpenShift Container Platform and see the additional tooling it provides to develop and manage more complex applications, please refer to the following links.

- [OpenShift 4.16 Documentation](https://docs.openshift.com/container-platform/4.16/welcome/index.html){target="_blank" rel="noopener"}
- [OpenShift Product Page](https://www.redhat.com/en/technologies/cloud-computing/openshift){target="_blank" rel="noopener"}
- [Red Hat Hybrid Cloud Blog](https://cloud.redhat.com/blog){target="_blank" rel="noopener"}
- [OpenShift Learning](https://developers.redhat.com/learn#assembly-id-70171){target="_blank" rel="noopener"}
- [OpenShift on IBM Z Datasheet](https://www.redhat.com/en/resources/openshift-ibm-z-linuxone-datasheet){target="_blank" rel="noopener"}