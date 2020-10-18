# Multiple VNETs with VMs

## Test bed for Azure Network Manager

[![Deploy to Azure](https://aka.ms/deploytoazurebutton)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fmddazure%2F101-multiple-vnets-with-vms%2Fmain%2Fazuredeploy.json)

This template deploys specified number of VNETs (1 - 254), each with a small Windows VM. 

Address space in each VNET is unique: 10.0.<1-254>.0.

Purpose is to provide a test environment for the private preview Azure Network Manager.

:exclamation: Your subscription must be white listed for the ANM private preview.

Usage:
- Create a resource group in West Central US.
- Deploy the template to the resource group.
- Deploy ANM to the resource group.
- Configure and test ANM per instructions provided in the white list message.

