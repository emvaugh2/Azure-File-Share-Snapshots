# Create and Restore File Share Snapshots in Azure

**There are 2 objectives with this lab:**
* Create a Storage Account and File Share
* Connect File Share to Windows VM
* Take a Snapshot and Restore Data

HAS NOT BEEN COMPLETED YET. 

## Create a Storage Account and File Share

We first need to be able to log into Azure using the Linux jumpbox provided in the lab. We're going to use a Service Principal to view information in the portal from the jumpbox. So lets launch the Terminal first and then SSH into the Linux VM/jumpbox using



## Connect File Share to Windows VM

So for the next task, we need to list the Azure role definitions and assignments using the Linux VM command line. Now I don't have much experience with Linux so I had to google a bunch of commands to see how to create a file, append a file, get a  JSON output, and etc.

I created a Notepad file with all the links I used but I'm sure I'll also post the links here as well. 

The first part of this tasks requires us to list the role definitions and output to a file named `roleinfo.json`. So we need to first find out the `az` command to list the role definitions so I found an article on the Microsoft Azure website ([link here](https://learn.microsoft.com/en-US/cli/azure/role/definition?view=azure-cli-latest#az-role-definition-list)). This is where I found the `az role definition list`. I received the following output. 





## Take a Snapshot and Restore Data


Lab completed!

## Personal Notes



