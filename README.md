# Deploy App in Azure AKS

1. First create "Resource Group" in Azure Portal
2. Create AKS Cluster
# az group list
# RG1=491-48123548-deploying-and-accessing-an-applicatio

# az aks create --resource-group $RG --name Cluster01 --node-count 3 --generate-ssh-keys --node-vm-size Standard_B2s --enable-managed-identity
# az aks get-credentials --name Cluster01 --resource-group $RG1

# kubectl apply -f deployment.yaml
# kubectl apply -f service.yaml
