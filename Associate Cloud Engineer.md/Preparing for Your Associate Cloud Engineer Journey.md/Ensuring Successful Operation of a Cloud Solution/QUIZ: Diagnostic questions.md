# Questions:

**1. You want to view a description of your available snapshots using the command line interface (CLI). What gcloud command should you use?**

a. gcloud compute snapshots get

b. gcloud compute list snapshots

c. gcloud compute snapshots list

d. gcloud snapshots list

**Ans:**

<br/>

**2. You have a scheduled snapshot you are trying to delete, but the operation returns an error. What should you do to resolve this problem?**

a. Detach the snapshot schedule before deleting it.

b. Restore the snapshot to a persistent disk before deleting it.

c. Delete the downstream incremental snapshots before deleting the main reference.

d. Delete the object the snapshot was created from.

**Ans:**

<br/>

**3. Cymbal Superstore has a subnetwork called mysubnet with an IP range of 10.1.2.0/24. You need to expand this subnet to include enough IP addresses for at most 2000 new users or devices. What should you do?**

a. gcloud compute networks subnets expand-ip-range mysubnet --region us-central1 --prefix-length 21

b. gcloud compute networks subnets expand-ip-range mysubnet --region us-cetnral1 --prefix-length 22

c. gcloud compute networks subnets expand-ip-range mysubnet --region us-central1 --prefix-length 20

d. gcloud networks subnets expand-ip-range mysubnet --region us-central1 --prefix-length 21

**Ans: d.**

<br/>

**4. What is the declarative way to initialize and update Kubernetes objects?**

a. kubectl replace

b. kubectl run

c. kubectl apply

d. kubectl create

**Ans:**

<br/>

**5. You have a Cloud Run service with a database backend. You want to limit the number of connections to your database. What should you do?**

a. Set CPU Utilization.

b. Set Concurrency settings.

c. Set Min instances.

d. Set Max instances.

**Ans: **

<br/>

**6. What Kubernetes object provides access to logic running in your cluster via endpoints that you define?**

a. Services

b. Deployments

c. Pod templates

d. Pods

**Ans: a.**

<br/>

**7. Which of the following tasks are part of the process when configuring a managed instance group? (Pick two.)**

a. Specifying Persistent disks

b. Choosing instance Machine type

c. Configuring the operating system

d. Defining Health checks

e. Providing Number of instances

**Ans: e. and d.**

<br/>

**8. Cymbal Superstore’s supply chain management system has been deployed and is working well. You are tasked with monitoring the system’s resources so you can react quickly to any problems. You want to ensure the CPU usage of each of your Compute Engine instances in us-central1 remains below 60%. You want an incident created if it exceeds this value for 5 minutes. You need to configure the proper alerting policy for this scenario. What should you do?**

a. Choose resource type of VM instance, and metric of CPU utilization, condition trigger if any time series violates, condition is below, threshold is .60 for 5 minutes.

b. Choose resource type of VM instance and metric of CPU utilization, condition trigger if any time series violates, condition is above, threshold is .60 for 5 minutes.

c. Choose resource type of VM instance and metric of CPU load, condition trigger if any time series violates, condition is below, threshold is .60, for 5 minutes.

d. Choose resource type of VM instance and metric of CPU utilization, condition trigger all time series violates, condition is above, threshold is .60 for 5 minutes.

**Ans: d.**

<br/>

**9. You want to implement a lifecycle rule that changes your storage type from standard to nearline after a specific date. What conditions should you use? (Pick two).**

a. MatchesStorageClass

b. IsLive

c. NumberofNewerVersions

d. Age

e. CreatedBefore

**Ans: a. and **

<br/>

**10. Cymbal Superstore’s GKE cluster requires an internal http(s) load balancer. You are creating the configuration files required for this resource. What is the proper setting for this scenario?**

a. Annotate your service object with a neg reference.

b. Implement custom static routes in your VPC:

c. Annotate your ingress object with an ingress.class of “gce.”

d. Configure your service object with a type: LoadBalancer.

<br/>





