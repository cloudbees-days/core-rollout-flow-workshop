class: center, middle

# CloudBees Core Workshop

![CloudBees Core](https://github.com/cloudbees-days/core-rollout-flow-workshop/raw/master/labs/core-casc/images/cloudbeescore_logo.png)

---

# Lab 1 - Core Setup

[https://github.com/cloudbees-days/core-rollout-flow-workshop](https://github.com/cloudbees-days/core-rollout-flow-workshop)

[INSERT CONTENT HERE]

---

# Lab 2 - Configuration as Code (CasC) for CloudBees Core

[https://github.com/cloudbees-days/core-rollout-flow-workshop/blob/master/labs/core-casc/core-casc.md](https://github.com/cloudbees-days/core-rollout-flow-workshop/blob/master/labs/core-casc/core-casc.md)

[INSERT CONTENT HERE]

---

# Lab 3 - Hibernating Masters

[https://github.com/cloudbees-days/core-rollout-flow-workshop/blob/master/labs/hibernating-masters/hibernating-masters.md](https://github.com/cloudbees-days/core-rollout-flow-workshop/blob/master/labs/hibernating-masters/hibernating-masters.md)

The [CloudBees Core Managed Master hibernation](https://docs.cloudbees.com/docs/cloudbees-core/latest/cloud-admin-guide/managing-masters#_hibernation_in_managed_masters) feature takes advantage of running Core on Kubernetes by automatically shutting down or hibernating Team/Managed Masters. This is done by scaling the Kubernetes StatefulSet down to zero replicas.

There are several ways that costs are reduced with Managed Master hibernation:

1. When using Kubernetes auto-scaling and a Managed Master is hibernated then the Kubernetes cluster has the potential to downscale by removing a node.
2. When a Managed Master is hibernated you immediately gain additional CPU and memory on the node where your Team/Managed Master pod was running - this additional capacity is immediately available for Kubernetes based agents reducing the possibility of agents queueing and/or triggering an upscaling of your Kubernetes cluster. 

[INSERT CONTENT HERE]

---

# Lab 4 - Pipeline Template Catalogs & Pipeline Policies

[https://github.com/cloudbees-days/core-rollout-flow-workshop/blob/master/labs/pipeline-template-catalog/pipeline-template-catalog.md](https://github.com/cloudbees-days/core-rollout-flow-workshop/blob/master/labs/pipeline-template-catalog/pipeline-template-catalog.md)

[INSERT CONTENT HERE]

---

# Lab 5 - Cross Team Collaboration

[https://github.com/cloudbees-days/core-rollout-flow-workshop/blob/master/labs/cross-team-collaboration/cross-team-collaboration.md](https://github.com/cloudbees-days/core-rollout-flow-workshop/blob/master/labs/cross-team-collaboration/cross-team-collaboration.md)

[INSERT CONTENT HERE]

---


class: center, middle

# Rollout Workshop

---

# Setup

[INSERT CONTENT HERE]