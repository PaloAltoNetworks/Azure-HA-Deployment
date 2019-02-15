# Azure-HA

We are planning to release the VM-Series 9.0 image in Azure soon. We will keep you updated on the progress. 

This template will allow you to launch a second VM-Series into an existing resource group because the Azure Marketplace will not allow that. 

You will still be responsible for configuring your own Azure HA settings within the Azure Portal and the VM-Series firewall. 

# In the meantime you can take the following steps

1. launch a VM-Series firewall using the latest which is 8.1
2. Upgrade to PAN-OS 9.0
3. Use Azure CLI to launch a VM-Series running PAN-OS 8.1 into the exact same Resource Group as the first firewall
4. Upgrade to PAN-OS 9.0


Please understand that when the template is launched it will NOT configure the necessary setting in Azure for HA. It will simply allow you to launch a second VM-Series into a resource group that has an existing VM-Series. 


# Support Policy: Community-Supported
The code and templates in this repository are released under an as-is, best effort, support policy. These scripts should viewed as community supported and Palo Alto Networks will contribute our expertise as and when possible. We do not provide technical support or help in using or troubleshooting the components of the project through our normal support options such as Palo Alto Networks support teams, or ASC (Authorized Support Centers) partners and backline support options. The underlying product used (the VM-Series firewall) by the scripts or templates are still supported, but the support is only for the product functionality and not for help in deploying or using the template or script itself. Unless explicitly tagged, all projects or work posted in our GitHub repository (at https://github.com/PaloAltoNetworks) or sites other than our official Downloads page on https://support.paloaltonetworks.com are provided under the best effort policy.
