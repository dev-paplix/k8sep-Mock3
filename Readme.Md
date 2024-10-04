Name:

Q1:
Upgrade your Kubeadm from the current version to the 1.31.1.* for all nodes

Q2:
Create a Persistent Volume with the given specification.
Volume Name: pv-analytics, Storage: 100Mi, Access modes: ReadWriteMany, Host Path: /pv/data-analytics

Q3:
create one pod including both nginx and redis

Q4:
Create a new user use RABC in your Kubenetes cluster and give it a power to create, get, logs, and describe the pods. Then create a new nginx pod use the new user

Q:5
Create a deployment of nginx with the image of nginx of version 1.18-alpine. Now upgrade the version to 1.19-alpine and record it. Now roll back the deployment to the previous version.


Q6:
Create a pod of jenkins with the image jenkins in the namespace of web-frontend


Q7:

Create a configuration file to create a pod of redis with redis image and 6 replicas with label app_env_stage=dev. The file should be placed under /opt/cka

Q8:
Used etcd to create a backup. Remove all or one of the previous deployments and restore the backup



Q9:
Create a manifest file to launch a myservice pod with an image of nginx on the worker node automatically. Any manifest files should be placed in /etc/kubernetes/manifests



Q10:

Create a statefulset for Mysql which gets the following information from the secret file in the opaque format:

MYSQL_ROOT_PASSWORD
MYSQL_DATABASE
MYSQL_PASSWORD
MYSQL_USER


Q11:

Create and phpmyadmin deployment and service use phpmyadmin:latest image which gets its "PMA_HOST" as an environmental variable from the service name from the previous question 


Q12:
Configure Horizontal Pod Autoscaling for a Deployment to automatically scale based on CPU usage.

Deployment Name: api-server Namespace: production Replica Set: Set initially to 2 replicas. Container Image: nginx:1.18 CPU Target: Scale the Deployment if the average CPU usage exceeds 50%. Minimum Pods: 2 Maximum Pods: 5

Q13:
Create a NetworkPolicy which denies all ingress traffic

Q14:

Create a deployment names  busybox:stable-glibc in the qq3 namespace. Perform a rolling update to the deployment by setting the image to busybox:stable-musl

Q15:

The cluster admin asked you to find out the following information about etcd running on controlplane:

Server private key location

Server certificate expiration date

Is client certificate authentication enabled

Q16:
Create a deployment and a service name apache with the image of httpd with a namespace of apache. The deployment must be visible from outside of the cluster with a port 80.


Q17:

Create a storageclass with 10Gi of space, then create a persistent volume claims that claims 4Gi of the storage


