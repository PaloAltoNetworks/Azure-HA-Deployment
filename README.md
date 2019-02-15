# Azure-HA

#Please Read
The Purpose of this template is to allow you to launch a second VM-Series into an existing resource group because the Azure Marketplace will not allow this. 

You will still be responsible for configuring your own Azure HA settings within the Azure Portal and the VM-Series firewall. Please refere to the VM-Series deployment guide for 9.0 for configuration details. [CLICK HERE](https://docs.paloaltonetworks.com/vm-series/9-0/vm-series-deployment/set-up-the-vm-series-firewall-on-azure/configure-activepassive-ha-for-vm-series-firewall-on-azure.html)


[<img src="http://azuredeploy.net/deploybutton.png"/>](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2FPaloAltoNetworks%2FAzure-HA-Deployment%2Fmaster%2Fazuredeploy.json?token=AZoiWXZHIcxPcJG4iqbfyOUvHN1O8coUks5ahgGXwA%3D%3D)

# Manual Approach

If you choose to take a different approach you can do the following

1. Launch a VM-Series firewall using the latest which is 8.1
2. Upgrade to PAN-OS 9.0
3. Use Azure CLI to launch a VM-Series running PAN-OS 8.1 into the exact same Resource Group as the first firewall
4. Upgrade to PAN-OS 9.0

For more information on how to use the Azure CLI. [CLICK HERE](https://docs.microsoft.com/en-us/cli/azure/?view=azure-cli-latest)  
For an Online Azure CLI shell use the following link and select the Powershell option. [CLICK HERE](https://shell.azure.com/)


# Support Policy: Community-Supported
The code and templates in this repository are released under an as-is, best effort, support policy. These scripts should viewed as community supported and Palo Alto Networks will contribute our expertise as and when possible. We do not provide technical support or help in using or troubleshooting the components of the project through our normal support options such as Palo Alto Networks support teams, or ASC (Authorized Support Centers) partners and backline support options. The underlying product used (the VM-Series firewall) by the scripts or templates are still supported, but the support is only for the product functionality and not for help in deploying or using the template or script itself. Unless explicitly tagged, all projects or work posted in our GitHub repository (at https://github.com/PaloAltoNetworks) or sites other than our official Downloads page on https://support.paloaltonetworks.com are provided under the best effort policy.
