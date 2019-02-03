title: Rancher
class: animation-fade
layout: true

<!-- This slide will serve as the base layout for all your slides -->
.bottom-bar[
  {{title}}
]

---

class: impact

# {{title}}
## Complete container management platform

---

# The basics

## Overview

Rancher is an open source software platform that enables organizations to run and manage Docker in production.

Rancher supplies the entire software stack needed to manage containers in production.

Rancher software consists of four major components:

---

# The basics

## Infrastructure Orchestration

Rancher takes in raw computing resources from any public or private cloud in the form of *Linux hosts*.
Each Linux host can be a virtual machine or physical machine. 

Rancher implements a portable layer of infrastructure services designed specifically to power containerized applications.

Rancher infrastructure services include **networking**, **storage**, **load balancer**, **DNS**, and **security**.

Rancher infrastructure services are typically deployed as containers themselves, so that the same Rancher infrastructure service can run on any Linux hosts from any cloud.

---

# The basics

## Container Orchestration and Scheduling

Rancher includes a distribution of all popular container orchestration and scheduling frameworks today, including *Docker Swarm*, *Kubernetes* and *Mesos*.
The same user can create multiple Swarm or Kubernetes clusters.
They can then use the native Swarm or Kubernetes tools to manage their applications.

In addition Rancher supports its own container orchestration and scheduling framework called **Cattle**.

Cattle is used extensively by Rancher to orchestrate infrastructure services as well as setting up, managing, and upgrading Swarm, Kubernetes, and Mesos clusters.

---

# The basics

## Application Catalog

Rancher users can deploy an entire multi-container clustered application from the application catalog with one click of a button.

Users can manage the deployed applications and perform fully automated upgrades when new versions of the application become available.

Rancher maintains a public catalog consisting of popular applications contributed by the Rancher community.

Rancher users can create their own private catalogs.

---

# The basics

## Enterprise-grade Control

Rancher supports flexible user authentication plugins and comes with pre-built user authentication integration with *Active Directory*, *LDAP*, and *GitHub*.

Rancher supports Role-Based Access Control (RBAC) at the level of environments, allowing users and groups to share or deny access to, for example, development and production environments.

The following figure illustrates Rancher’s major components and features.

---

# The basics

.responsive[![](./images/rancher_overview.png)]









