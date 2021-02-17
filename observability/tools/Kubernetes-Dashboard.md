# Kubernetes Dashboard

This document covers the [Kubernetes Dashboard](https://github.com/kubernetes/dashboard) which is a useful tool for remote debugging Kubernetes Clusters. It allows the management of applications running in the cluster, debug them and manage the cluster all through this dashboard.

## Overview and Background

There are times when not all solutions can be run locally. This limitation could be due to a cloud service which does not offer a robust or efficient way to locally debug the environment. In these cases, it is necessary to use other tools that enable remote debugging. One such example is the Kubernetes Dashboard.

## Pre-Requisites

- [Kubernetes cluster up and running](https://docs.microsoft.com/en-us/azure/aks/kubernetes-walkthrough)
- [Install Kubectl](https://kubernetes.io/docs/tasks/tools/install-kubectl/): command-line tool that allows you to run commands against Kubernetes clusters.

## Advantages and Use Cases

- Allows the ability to view, manage and monitor the operational aspects of the Kubernetes Cluster.

- Provides an easy to use web-based UI to be able to do do the following:
  - see an overview of the cluster
  - deploy applications onto the cluster
  - troubleshoot applications running on the cluster
  - view, create, modify, and delete Kubernetes resources
  - view basic resource metrics including resource usage for Kubernetes objects
  - view and access logs
  - exec into the container
  - live view of the pods state (e.g. started, terminating, etc)

## Limitations

- Cannot run Kubernetes dashboard in Cloud Shell
- Customizations of themes, layouts, and other UI elements

## References

- [Kubernetes Dashboard Repository](https://github.com/kubernetes/dashboard)
- [Dashboard Usage and Examples](https://kubernetes.io/docs/tasks/access-application-cluster/web-ui-dashboard/)
- [Kubectl Cheat Sheet and Operations](https://kubernetes.io/docs/reference/kubectl/overview/)
- [Alternatives to Kubernetes Dashboard](https://octopus.com/blog/alternative-kubernetes-dashboards)
