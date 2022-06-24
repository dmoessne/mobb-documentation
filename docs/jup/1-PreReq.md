## Prerequisites

#### 1. A OpenShift Cluster
This lab will assume you have already provisioned a OpenShift cluster succesfully and are able to use it.  

#### 2. OpenShift Command Line Interface
Please see the [OpenShift Command Line section](https://docs.openshift.com/container-platform/4.10/cli_reference/openshift_cli/getting-started-cli.html) for more information on installing.

The following guides through a step by step procedure in deploying Jupyter Notebook in OpenShift.

### What will we do in this lab?
In this lab, you’ll go through a set of tasks that will help you understand the concepts of deploying and using containers.

Some of the things you’ll be going through:

- Create a minimal Jupyter notebook image using the Source-to-Image (S2I) build process. The image can be built in OpenShift, separately using the s2i tool, or using a docker build.
- Deploy a custom notebook image, you can use the s2i-minimal-notebook:3.6 image as an S2I builder

You’ll be doing the majority of the labs using the OpenShift CLI, but you can also accomplish them using the OpenShift web console.

The Jupyter Project provides a number of images for notebooks on Docker Hub. These are:

* base-notebook
* r-notebook
* minimal-notebook
* scipy-notebook
* tensorflow-notebook
* datascience-notebook
* pyspark-notebook
* all-spark-notebook

The GitHub repository used to create these is:

* https://github.com/jupyter/docker-stacks


