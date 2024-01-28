# AzureVMCREATE
For my students on how to create a VM using CLI
Step 1: `az vm create` means you're telling a tool called "az" to create a virtual machine (VM). 
Step 2:`--resource-group "[sandbox resource group name]"` means you're putting this VM in a group of other resources, which helps organize things. You need to replace `[sandbox resource group name]` with the actual name of the resource group you want to use.  
Step 3: `--name my-vm` means you're giving your new VM a name, which in this case is "my-vm".  
Step 4: `--public-ip-sku Standard` means you want your VM to have a standard type of public IP address.  
Step 5: `--image Ubuntu2204` means you want to use an image of Ubuntu version 22.04 to set up your VM.  
Step 6: `--admin-username azureuser` means you want to create a user named "azureuser" with administrative privileges on this VM.  
Step 7: `--generate-ssh-keys` means you want the tool to automatically create SSH keys for you. SSH keys are a way to securely connect to your VM over the internet.  
So, in simple terms, this command is telling a tool to create a new virtual machine named "my-vm" using Ubuntu version 22.04, with a standard public IP address, in a specific resource group. It also sets up a user named "azureuser" with administrative privileges and generates SSH keys for secure access.
