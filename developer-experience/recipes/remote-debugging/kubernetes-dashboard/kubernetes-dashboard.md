# Remote Debugging using the Kubernetes Dashboard

This document covers the Kubernetes Dashboard which is a useful tool for remote debugging for Kubernetes Clusters. It allows the management of applications running in the cluster, debug them and manage the cluster all through this dashboard.

## Overview and Background

Developer experience focuses on how easy or difficult it is for a developer to perform essential tasks needed to implement a change including build, test, start, and debug.

There are times when not all solutions can be run locally. This limitation could be due to a cloud service which does not offer a robust or efficient way to locally debug the environment. In these cases, it is necessary to deploy use other tools that enabling this remote debugging. One such example is the Kubernetes dashboard.

## Pre-Requisites

- Kubernetes cluster up and running
- [Install Kubectl](https://kubernetes.io/docs/tasks/tools/install-kubectl/): command-line tool that allows you to run commands against Kubernetes clusters.

## Advantages

- Allows the ability to view, manage and monitor the operational aspects of the Kubernetes Cluster.

- Provides an easy to use web-based UI to be able to do do the following:
  - See an overview of the cluster
  - deploy applications onto the cluster
  - troubleshoot applications running on the cluster
  - view, create, modify, and delete Kubernetes resources
  - view basic resource metrics including resource usage for Kubernetes objects
  - viewing and accessing logs

## Limitations/Out of Scope

- Cannot run Kubernetes dashboard in Cloud Shell

## Usage

- TBA

## References

- [Kubernetes Dashboard Repository](https://github.com/kubernetes/dashboard)
- [Dashboard Usage and Examples](https://kubernetes.io/docs/tasks/access-application-cluster/web-ui-dashboard/)
- [Kubectl Cheat Sheet and Operations](https://kubernetes.io/docs/reference/kubectl/overview/)
- [Alternatives to Kubernetes Dashboard](https://octopus.com/blog/alternative-kubernetes-dashboards)