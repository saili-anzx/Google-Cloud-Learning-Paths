# Questions:

**1. Cymbal Superstore has a subnetwork called mysubnet with an IP range of 10.1.2.0/24. You need to expand this subnet to include enough IP addresses for at most 2000 new users or devices. What should you do?**

a. gcloud compute networks subnets expand-ip-range mysubnet --region us-cetnral1 --prefix-length 22

b. gcloud compute networks subnets expand-ip-range mysubnet --region us-central1 --prefix-length 20

c. gcloud compute networks subnets expand-ip-range mysubnet --region us-central1 --prefix-length 21

d. gcloud networks subnets expand-ip-range mysubnet --region us-central1 --prefix-length 21

**Ans:**

<br/>

**2. Cymbal Superstore’s supply chain management system has been deployed and is working well. You are tasked with monitoring the system’s resources so you can react quickly to any problems. You want to ensure the CPU usage of each of your Compute Engine instances in us-central1 remains below 60%. You want an incident created if it exceeds this value for 5 minutes. You need to configure the proper alerting policy for this scenario. What should you do?**

a. Choose resource type of VM instance and metric of CPU utilization, condition trigger if any time series violates, condition is above, threshold is .60 for 5 minutes.

b. Choose resource type of VM instance and metric of CPU load, condition trigger if any time series violates, condition is below, threshold is .60, for 5 minutes.

c. Choose resource type of VM instance, and metric of CPU utilization, condition trigger if any time series violates, condition is below, threshold is .60 for 5 minutes.

d. Choose resource type of VM instance and metric of CPU utilization, condition trigger all time series violates, condition is above, threshold is .60 for 5 minutes.

**Ans:**

<br/>

**3. You have a scheduled snapshot you are trying to delete, but the operation returns an error. What should you do to resolve this problem?**

a. Restore the snapshot to a persistent disk before deleting it.

b. Delete the downstream incremental snapshots before deleting the main reference.

c. Detach the snapshot schedule before deleting it.

d. Delete the object the snapshot was created from.

**Ans:**

<br/>

**4. Which of the following tasks are part of the process when configuring a managed instance group? (Pick two.)**

a. Choosing instance Machine type

b. Defining Health checks

c. Specifying Persistent disks

d. Configuring the operating system

e. Providing Number of instances

**Ans: b. and **

<br/>

**5. What Kubernetes object provides access to logic running in your cluster via endpoints that you define?**

a. Deployments

b. Pod templates

c. Services

d. Pods

**Ans: c.**

<br/>

**6. You want to implement a lifecycle rule that changes your storage type from standard to nearline after a specific date. What conditions should you use? (Pick two).**

a. IsLive

b. Age

c. MatchesStorageClass

d. NumberofNewerVersions

e. CreatedBefore

**Ans: c. and **

<br/>

**7. What is the declarative way to initialize and update Kubernetes objects?**

a. kubectl run

b. kubectl apply

c. kubectl replace

d. kubectl create

**Ans: b.**

<br/>

**8. You have a Cloud Run service with a database backend. You want to limit the number of connections to your database. What should you do?**

a. Set Concurrency settings.

b. Set Min instances.

c. Set CPU Utilization.

d. Set Max instances.

**Ans:**

<br/>

**9. You want to view a description of your available snapshots using the command line interface (CLI). What gcloud command should you use?**

a. gcloud compute list snapshots

b. gcloud compute snapshots list

c. gcloud compute snapshots get

d. gcloud snapshots list

**Ans: b.**

<br/>

**10. Cymbal Superstore’s GKE cluster requires an internal http(s) load balancer. You are creating the configuration files required for this resource. What is the proper setting for this scenario?**

a. Implement custom static routes in your VPC:

b. Annotate your ingress object with an ingress.class of “gce.”

c. Annotate your service object with a neg reference.

d. Configure your service object with a type: LoadBalancer.

**Ans:**

<br/>


