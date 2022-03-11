Please follow These steps:

1. Create a project in Azure Devops.
2.a.Under that project create a connnection between your github account.
-->go to project settings -->service connection --> add new connection --> put your github account credentials 
2.b.Same way add docker hub account.
2.c.Create a 2 nodes kubernetes cluster in your local vm .You can follow this link to do this https://www.tecmint.com/install-a-kubernetes-cluster-on-centos-8/
2.d.Add a azure agent in your local kubernetes cluster master node. You can follow this link to do this https://docs.microsoft.com/en-us/azure/devops/pipelines/agents/v2-linux?view=azure-devops
2.e.Follow step 2.a to create a connection between your K8s cluster and azure devops pipeline . You can use kubeconfig file. to get kubeconfig use command "kubectl config view --raw"  
3.Now run the pipeline from azure devops to check the deployment


====================Thanks & enjoy automations======================= 
