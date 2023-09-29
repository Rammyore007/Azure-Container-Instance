# Azure-Container Instances
Azure Container Instances (ACI) is a serverless container service that allows user to delpoy and run containerized applications without the need to manage the underlying infrasture.
## Creating an ACI
1. sign in to microsoft azure
2. Search for container instances
3. Click on + sign to create a new container
4. it will take you to the next page which has Basic, Networking, Tags and Review and create icons
5. Under the Basic tab, you will fill out the following;
   a. Subscription: Azure Sponsorship
   b. Resource Group: Cloudtrainer
   c. Container name: mycontainer
   d. Region: East US
   e. Image source: other registry
   f. Image type: Public
   g. Image: mcr.microsoft.com/azuredocs/aci-helloworld
   h. OS type: Linux

6. Click on Next moving to the networking Tab
7. Fill the Dns name label with mycontainerdnsxxxxx
8. Click on Review + Create
9. Validation passed and you can download the template if necessary
10. Click on Create
11. Notification is gotten when the deployment is successful

### Verifying the ACI deployed
1. Go to resources on the deployment page
2. Check the status if its running
3. Copy the FQDN and paste into a browse: mycontainerdnsxxxxx.crhmhvakacfrhrhm.eastus.azurecontainer.io
4. You will see the pop up welcoming you to Azure Container Instances
5. ![image](https://github.com/Rammyore007/Azure-Container-Instance/assets/145805366/244473e0-968b-45ab-b611-1a2eb47f6cdd)
