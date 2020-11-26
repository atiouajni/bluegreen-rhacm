# Introduction

This repository contains all necessary steps and manifests to demonstrate RHACM capabilities.

After completing this tutorial you will be able to accomplish the following tasks:

- Multi-cluster lifecycle management
- Observability capabilities
- Multi-cluster day 2 management and configuration (policy, governance)
- Application lifecyle management

[![Screenshot of store homepage](./docs/img/acm-cluster-overview.png)](./docs/img/acm-cluster-overview.png) 

# Requirements
 - Openshift 4.5+ declared as a Hub
 - Openshift 4.5+ declared as a managed cluster
 - oc cli 

# Setup

**Connet to the Hub bastion and deploy ACM manifests :**

```shell
ssh id@server

#Deploy ACM Application, subscription, Channel and policies
git clone https://github.com/atiouajni/bluegreen-rhacm.git
cd bluegreen-rhacm
oc new-project bluegreen
oc apply -f rhacm-manifests/

oc new-project rhacm-policies
oc apply -f rhacm-manifests/policies
```
# Installation

# Usage

# Encountered issues

**Issue :**
status:
  lastUpdateTime: '2020-11-25T10:23:04Z'
  message: Active
  phase: PropagationFailed
  reason: couldn't find remote ref "refs/heads/master"
**Issue :**
Edit the subscription manifest and add these labels with your specific branch and path
    apps.open-cluster-management.io/git-path: openshift-manifests/bluegreen-php
    apps.open-cluster-management.io/git-branch: main
# Cleanup

# Documentation

# Released versions

