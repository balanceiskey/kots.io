---
date: "2020-02-20T00:00:00Z"
lastmod: "2020-02-20T00:00:00Z"
title: "Guides"
weight: "2"
---

End-to-end guides to get you up and running with KOTS quickly.

### Getting Started

###### [Quickstart](/vendor/guides/quickstart)

The KOTS Quickstart is our simplest guide, we'll get running quickly with a simple Nginx application in Kubernetes using a single VM. 

###### [Existing Cluster](/vendor/guides/existing-cluster)

The KOTS Existing Cluster Guide is another of our simplest guides. We'll get running quickly with a simple Nginx application on an existing cluster in GKE (or another cluster you have handy). 


### Next Steps

These guides will assume you've completed one of the previous guides for either [Embedded Cluster](/vendor/guides/quickstart) or [Existing Cluster](/vendor/guides/existing-cluster) delivery.

###### [Integrate Persistent Datastores](/vendor/guides/persistent-datastores)

In this guide, we'll review best practices for integrating persistent stores like databases, queues, and caches. We'll explore ways to give your end user the option to either embed an instance with the application, or connect your application to an external cluster that they will manage. We'll use a PostgreSQL database as an example, configuring an example app to connect.

###### [Prepare for Production Deploys](/vendor/guides/production-ready)

This guide is intended as a lightweight checklist to ensure you have explored all the features of KOTS and integrated the ones that will help ensure your end users are most likely to be successful deploying and running your KOTS application

<!-- Coming Soon!

###### [Package a Helm Chart](/vendor/guides/helm-chart)

In this guide, we'll explore how you can leverage the wealth of software bundled using Helm to integrate an off-the-shelf application into your KOTS app bundle. We'll use the Consul helm chart as an example in this case.

###### [Integrate Collectors and Analyzers for Troubleshooting](/vendor/guides/troubleshoot-support-bundle)

###### [Add custom Prometheus Graphs](/vendor/guides/prometheus-graphs)

###### [Manage Customer Entitlements](/vendor/guides/entitlements)

## Advanced

###### [Runtime License Validation](/vendor/guides/runtime-license-validation)

#### [Advanced Embedded Cluster Usage](/vendor/guides/advanced-embedded-cluster)

- locking component versions
- staging Installer YAMLs through Unstable/Beta/Stable channels
- manging YAML in git repo
- preflight checks for embedded components when running in existing cluster (e.g. storageclass)

#### [Airgapped Existing Cluster](/vendor/guides/operator-airgap)

#### [Deploy an Operator to an airgapped cluster](/vendor/guides/operator-airgap)

#### [Deploy a Helm Chart to an airgapped cluster](/vendor/guides/helm-airgap)

#### [Deploy a Custom Preflight Check](/vendor/guides/custom-preflight)

#### [GitOps Workflow](/vendor/guides/gitops)

(Coming soon)

-->