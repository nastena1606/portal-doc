# Launch free Kubernetes clusters

Launch a free Kubernetes cluster with three worker nodes, 4 CPUs and 8 GB of RAM straight from [Percona Portal](https://portal.percona.com). You can create one free cluster per day. 

Free clusters expire in three hours. This makes them ideal for testing out PMM with DBaaS and Percona Operators in a native Kubernetes experience. 

<img width="1440" alt="Screenshot 2022-09-14 at 09 31 02" src="https://user-images.githubusercontent.com/62939655/190077890-1d52f330-0a36-4577-b383-a677f56cc5e7.png">

To launch a free cluster:

1. In the **Free Kubernetes** tab, select **Launch a new cluster**. Percona Platform starts provisioning the cluster, which can take a few minutes.  
2. Once the cluster is created, click **Show kubeconfig**.
3. Click **Copy to clipboard** in the **Kubernetes Cluster Configuration**.
4. Go to your PMM instance and [Add your new Kubernetes cluster](https://docs.percona.com/percona-monitoring-and-management/using/dbaas.html#kubernetes-clusters).

For more information about working with clusters in PMM, see [Private DBaaS with Free Kubernetes Cluster blogpost](https://www.percona.com/blog/private-dbaas-with-free-kubernetes-cluster/).
