# Container Image Scanning Playbook 
**Author: Safeena Begum**

Azure Defender for container registries brings deeper visibility into the vulnerabilities effecting the container image. 
This automation playbook will help you receive an email notification for any newfound vulnerabilities (findings) per image, compared to the last scan of the same image. This becomes more critical with the introduction of "continuous scans" where the same image would be rescanned on a daily basis.  

***

You can deploy the main template by clicking on the buttons below:

<a href="https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2FAzure%2FAzure-Security-Center%2Fmaster%2FWorkflow%2520automation%2FContainerImageScanning_Notification%2Fazuredeploy.json" target="_blank">
    <img src="https://aka.ms/deploytoazurebutton"/>
</a>
<a href="https://portal.azure.us/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2FAzure%2FAzure-Security-Center%2Fmaster%2FWorkflow%2520automation%2FContainerImageScanning_Notification%2Fazuredeploy.json" target="_blank">
<img src="https://raw.githubusercontent.com/Azure/azure-quickstart-templates/master/1-CONTRIBUTION-GUIDE/images/deploytoazuregov.png"/>
</a> 

***
