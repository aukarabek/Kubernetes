# kubernetes
All kubernetes related stuff

This small yet straightforward project describes how to manually deploy Kubernetes cluster on AWS using EC2 instances.

I used multiple EC2 machines, one acted as the K8s master node that hosted the control plane, and the other two instances configured in worker node roles.

Deploying directly to EC2 gives full control over the cluster, including its control plane components. 

This could make it easier to configure Kubernetes for more experienced engineers.

And remember that manually administering Kubernetes increases the maintenance overheads and can be daunting to inexperienced operators. 

You will be responsible for applying cluster upgrades and preserving reliability. 

It’s also challenging to configure auto-scaling for non-managed compute instances, which can affect the cluster’s long-term suitability.


