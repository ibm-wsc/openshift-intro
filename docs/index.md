# Introduction to Red Hat OpenShift

In this tutorial, you will walk through an introduction to OpenShift Container Platform (OCP) from both the web console and the OpenShift command line interface, `oc`. This tutorial is based on the [Getting Started](https://docs.openshift.com/container-platform/4.16/getting_started/openshift-web-console.html){target="_blank" rel="noopener"} portion of the OpenShift Container Platform documentation, but modified to run on various platform architectures (including IBM Z, IBM Power, and x86) as well as adding more explanations for the concepts it covers.

## Pre-Requisites

1. Access to an OpenShift cluster
2. `oc` CLI [installed](https://docs.openshift.com/container-platform/4.16/cli_reference/openshift_cli/getting-started-cli.html){target="_blank" rel="noopener"}
3. Projects created for each user with the names `userNN-project` (`NN` being each user number). Administrators can create this ahead of time with any limitations or quotas they wish, or administrators can allow users to create their own projects.

If you are going through this lab during a workshop provided by the IBM Z Washington Systems Center, these pre-requisites are already fulfilled in the environment you were provided.
