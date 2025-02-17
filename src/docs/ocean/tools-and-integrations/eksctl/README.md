# eksctl

[eksctl AWS CLI](https://aws.amazon.com/blogs/opensource/eksctl-eks-cli/) is an open-source CLI that lets you easily create Elastic Kubernetes Service (EKS) clusters. One of the benefits of EKS is that the Kubernetes control plane is handled entirely by AWS, freeing you from managing high availability for your control plane(s) and handling ongoing maintenance, such as Kubernetes upgrades.

However, when it comes to your clusters' worker nodes, you still need to find a solution that simplifies container infrastructure management by handling challenges like:

- Unavailable resources due to autoscaling that only look at cluster CPU and Memory and not actual Pod requirements
- Cost visibility (showback) that allocates spend based on namespaces, resources, labels, and annotations
- Pod rightsizing based on analysis of their actual resource consumption
- Handling immediate container scaling for high-priority workloads
- Reducing cloud infrastructure costs using spot instances and preemptible VMs

Ocean takes care of time-consuming DevOps activities, with container-driven autoscaling, cloud-native cost allocation, vertical rightsizing, a customizable buffer of spare nodes, and optimized utilization of the perfect blend of spot instances, reserved capacity, and on-demand resources.

Integration with excel lets you streamline and optimize the entire EKS process, from initially creating your cluster to managing and optimizing it on an ongoing basis.

## Related Links

- [Create a New Cluster with eksctl](ocean/tools-and-integrations/eksctl/create-a-new-cluster-with-eksctl)
- [Connect an Existing Cluster](ocean/tools-and-integrations/eksctl/join-an-existing-cluster) to Ocean using eksctl.
- Learn more about [eksctl](https://github.com/spotinst/weaveworks-eksctl).
