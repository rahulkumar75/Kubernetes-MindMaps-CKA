# Kubernetes MindMaps (CKA)

Visual mind maps covering core Kubernetes and CKA exam concepts — architecture, workloads, networking, storage, and security — organized for sequential learning.

Each `.md` file breaks down one Kubernetes concept into a mind-map style outline: quick to skim, easy to revise from, and structured to match how the topic is actually tested on the **Certified Kubernetes Administrator (CKA)** exam.

## How to use this repo

Go folder by folder, in order (`01` → `10`). Each folder builds on the concepts from the one before it — start with the fundamentals, work through cluster architecture, then workloads, networking, storage, and security, finishing with interview prep.

## Contents

### 01 · Fundamentals
- [Docker](01-Fundamentals/Docker.md)
- [Docker Commands](01-Fundamentals/Docker-Commands.md)
- [Git](01-Fundamentals/git.md)

### 02 · Cluster Architecture
- [Kubernetes Architecture](02-Cluster-Architecture/Kubernetes-Architecture.md)
- [ETCD](02-Cluster-Architecture/ETCD.md)
- [Cluster](02-Cluster-Architecture/cluster.md)
- [CoreDNS](02-Cluster-Architecture/CoreDNS.md)

### 03 · Workloads & Scheduling
- [Scheduling](03-Workloads-Scheduling/Scheduling.md)
- [Scheduling MindMap](03-Workloads-Scheduling/Scheduling-MindMap.md)
- [Taints & Tolerations](03-Workloads-Scheduling/Taint-Tolerance.md)
- [Pod Priority & Preemption](03-Workloads-Scheduling/Pod-Priority-Preemption.md)
- [ReplicaSet & Deployment](03-Workloads-Scheduling/ReplicaSet-Deployment.md)
- [DaemonSet, Job & CronJob](03-Workloads-Scheduling/Daemonset-Job-Cronob.md)
- [StatefulSet & Volume Claims](03-Workloads-Scheduling/StatefulSet-VolumeClaim.md)
- [Horizontal Pod Autoscaler](03-Workloads-Scheduling/HPA-MindMap.md)
- [Init Containers](03-Workloads-Scheduling/init-container.md)
- [Probes](03-Workloads-Scheduling/Probes.md)

### 04 · Configuration
- [ConfigMaps & Secrets](04-Configuration/Configmap-Secrets.md)
- [Service Accounts](04-Configuration/service-account.md)

### 05 · Networking
- [Networking & Traffic Flow](05-Networking/Networking-Traffic-flow.md)
- [DNS](05-Networking/DNS.md)
- [Services](05-Networking/Services.md)
- [Ingress](05-Networking/Ingress.md)
- [Gateway API](05-Networking/GatewayAPI.md)
- [Network Policy](05-Networking/NetworkPolicy.md)
- [SSL/TLS](05-Networking/SSL-TLS.md)

### 06 · Storage
- [PV, PVC & StorageClass](06-Storage/PV-PVC-SC.md)
- [StorageClass & Dynamic Provisioning](06-Storage/storageClass-DynamicProvision.md)
- [Resource Requests & Limits](06-Storage/Resources-Req-Limits.md)
- [Resource QoS Classes](06-Storage/Resources-Qos-Class.md)

### 07 · Security
- [RBAC](07-Security/RBAC.md)
- [Admission Controllers](07-Security/Admission-Controllers.md)
- [Pod Security Standards](07-Security/Pod-Security-std.md)

### 08 · Extensibility
- [CRDs & Custom Resources](08-Extensibility/CRDs-CR.md)
- [Operators](08-Extensibility/Operators.md)
- [Helm](08-Extensibility/Helm.md)
- [Kustomize](08-Extensibility/Kustomize.md)

### 09 · Maintenance
- [Kubernetes Version Upgrade](09-Maintenance/K8s-Version-upgrade.md)

### 10 · Interview Prep
- [Kubernetes Interview MindMap](10-Interview-Prep/Kubernetes-InterviewMindMap.md)

## Related

Part of the broader [Kubernetes-CKA-Journey](https://github.com/rahulkumar75/Kubernetes-CKA-Journey) repo, which covers hands-on labs and notes alongside these mind maps.

## Contributing / Feedback

This is a personal study repo, but corrections or suggestions via issues/PRs are welcome.
