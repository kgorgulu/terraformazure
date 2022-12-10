# terraformazure
Step by Step creating Resource Group, VM, Storage Account with Terraform in Azure.
Resource Group
Open VS Code and create and name a new folder (ctrl+O),
Create new file and name it main.tf
In the file past the script
from the terminal, first, login your az portal with using “az login” command.
After login your azure portal, provision below commands: terraform init terraform plan terraform apply
VM
To get VM first we should find Windows virtual machine script from terraform web site; https://registry.terraform.io/providers/hashicorp/azurerm/latest/docs/resources/windows_virtual_machine

As a second step copy all code from webpage to VS code:

To create VM we should create. RG Virtual network Subnet NIC IP User ID and password OS

3. Storage Account:
On the terraform website find azurerm_storage_account https://registry.terraform.io/providers/hashicorp/azurerm/latest/docs/resources/storage_account

copy and paste entire template into VS Code and follow the steps as part one. 
