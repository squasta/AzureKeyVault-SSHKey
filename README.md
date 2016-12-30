# AzureKeyVault-SSHKey
PowerShell and ARM Template to deploy an Linux VM on Azure with SSH public key stored in Azure Key Vault


This script and ARM template will 

1- Create an Azure Key Vault

2- Create a secret (here an SSH public key) in this Key Vault

3- Deploy a Linux VM with its SSH public key from Azure Key Vault


You need : an Azure Subscription, Azure PowerShell module and a SSH public key


