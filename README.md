# temp_notes

https://blog.nestybox.com/2022/01/03/dink.html

https://github.com/nestybox/sysbox/blob/master/docs/user-guide/install-k8s.md

wget -q https://aka.ms/installazurecli-linux
curl -L https://aka.ms/installazurecli-linux --output installazurecli-linux
sudo bash installazurecli-linux


https://learn.microsoft.com/en-us/azure/aks/azure-files-csi

https://learn.microsoft.com/en-us/azure/aks/azure-files-csi#use-a-persistent-volume-with-private-azure-files-storage-private-endpoint

https://carlos.mendible.com/2021/08/02/aks-persistent-volume-claim-with-an-azure-file-storage-protected-with-a-private-endpoint/

https://github.com/kubernetes-sigs/azuredisk-csi-driver/blob/master/docs/install-csi-driver-v1.30.0.md

az account set --subscription 4b3ba83a-3165-41db-bd36-0bffb018aff0
az aks get-credentials --resource-group temp --name temp --overwrite-existing

Invoke-WebRequest -Uri "https://raw.githubusercontent.com/kubernetes-sigs/azuredisk-csi-driver/v1.30.0/deploy/install-driver.sh" -UseBasicParsing | Invoke-Expression; install-driver.sh v1.30.0 snapshot
