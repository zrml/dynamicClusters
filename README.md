# dynamicClusters

## Streamlining Kubernetes Cluster Provisioning with ArgoCD, Sveltos, and ClusterAPI

Tired of manually managing Kubernetes environments? 
This tutorial automates the process of creating dedicated EKS clusters on demand. We'll leverage a GitOps workflow, where a simple pull request triggers the creation of a new user's cluster. This powerful combination uses 
1. ArgoCD for cluster state management
2. Sveltos for change detection, solution orchestration and cluster provisioning & deletion and
3. ClusterAPI for EKS cluster creation.

Learn how to build a scalable and robust cluster provisioning pipeline—hands-on!

Key Features:

- Automated Cluster Creation: With every new user a cluster is provisioned automatically via a pull requests.
- GitOps Workflow: Leverages ArgoCD for maintaining the desired state
- Efficient Orchestration: Sveltos detects changes and orchestrates cluster creation and the addition of the defined addon packages 
- Scalable Infrastructure: ClusterAPI handles EKS cluster provisioning
- Hands-on Tutorial: Provides a practical guide for building the pipeline

