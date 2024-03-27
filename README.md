<h1>Azure Resource Group Tutorial</h1>

<h2>Description</h2>
In this lab, I'll show you how to create your first resource group in Azure. In our Azure resource group, we will create a Windows 10 VM (virtual machine) and a Windows Server VM. Resorces, according to Microsoft, are instances of services that you can create, such as virtual machines, storage, and SQL databases. And resource groups are logical containers where you can deploy and manage Azure resources like web apps, databases, and storage accounts. https://learn.microsoft.com/en-us/azure/cloud-adoption-framework/ready/azure-setup-guide/organize-resources
<br />

<h2>Environments Used </h2>

- <b>Windows 10</b> (21H2)
- <b>Windows Server 2019</b>

<h2>Setting up Azure Account:</h2>
<p align="center">
Click on the following video and follow the instructions to set up your free azure account (https://youtu.be/-0mL7rA8nhM?si=14lvwNCtXV5hMkIg): <br/>

<h2>Creating a resource group and VMs:</h2>

<p align="center">
First, we will go to https://portal.azure.com and log in. Once logged in, you will arrive at the following page: Click on resource groups or search for it in the search bar if it doesn't appear for you.: <br/>
<img src="https://imgur.com/Dads5U8.png" height="80%" width="80%" alt=/>
<br />
<br />
Select create:  <br/>
<img src="https://imgur.com/YY5zizz.png" height="80%" width="80%" alt=""/>
<br />
<br />
Next, we will name our resource group, then click review + create.: <br/>
<img src="https://imgur.com/Vc9a3UJ.png" height="80%" width="80%" alt=""/>
<br />
<br />
Then we will click create:  <br/>
<img src="https://imgur.com/aYjVYit.png" height="80%" width="80%" alt=""/>
<br />
<br />
You should now see the resource group you created in the portal:  <br/>
<img src="https://imgur.com/14ct0wI.png" height="80%" width="80%" alt=""/>
<br />
<br />
Next, we will go back to https://portal.azure.com and click on virtual machines. Once again, if you don't see it on your home page, search for it in the search bar.:  <br/>
<img src="https://imgur.com/kv7Ngz3.png" height="80%" width="80%" alt=""/>
<br />
<br />
Click on create on the top left corner and select virtual machine:  <br/>
<img src="https://imgur.com/tjTt9N1.png" height="80%" width="80%" alt=""/>
<br />
<br />
We will select the resource group we created for the resource group selection. Next, follow the same selections I made for the following instance details. If you select a certain region and don't see the same options as me, try changing your regions until you have the same configurations as me.:  <br/>
<img src="https://imgur.com/rKF2xcb.png" height="80%" width="80%" alt=""/>
<br />
<br />
Create a username and password that are unique to your VM, and make sure to have them saved somewhere. We will need it later. Click on the box next to licensing on the bottom left:  <br/>
<img src="https://imgur.com/53vcdrA.png" height="80%" width="80%" alt=""/>
<br />
<br />
Select Standard SSD:  <br/>
<img src="https://imgur.com/Nlz1IH7.png" height="80%" width="80%" alt=""/>
<br />
<br />
The virtual network and subnets ahould automatically be created for you by Azure as seen in the following image. Then we will click create + review:  <br/>
<img src="https://imgur.com/XsogsFB.png" height="80%" width="80%" alt=""/>
<br />
<br />
You will see validation passed then we will click create:  <br/>
<img src="https://imgur.com/Z47z7Bq.png" height="80%" width="80%" alt=""/>
<br />
<br />
Azure will start the deployment process of the virtual machine. Be patient as this process could take a while:  <br/>
<img src="https://imgur.com/gtuhbEZ.png" height="80%" width="80%" alt=""/>
<br />
<br />
Once the deployment process is done, go back to https://portal.azure.com and click on virtual machines, and you should see the Windows 10 VM there.:  <br/>
<img src="https://imgur.com/kT1PcsC.png" height="80%" width="80%" alt=""/>
<br />
<br />
Next, we will create a Windows Server 2019 VM. We will follow the same exact process, with the only difference being that we will select Windows Server 2019 for the image instead of Windows 10 Pro:  <br/>
<img src="https://imgur.com/c0YbMDr.png" height="80%" width="80%" alt=""/>
<br />
<br />
<img src="https://imgur.com/9XDYpEA.png" height="80%" width="80%" alt=""/>
<br />
<br />
<img src="https://imgur.com/VBpNQBS.png" height="80%" width="80%" alt=""/>
<br />
<br />
<img src="https://imgur.com/nQmlJle.png" height="80%" width="80%" alt=""/>
<br />
<br />
<img src="https://imgur.com/aMEv1EW.png" height="80%" width="80%" alt=""/>
<br />
<br />
<img src="https://imgur.com/ckYc27H.png" height="80%" width="80%" alt=""/>
<br />
<br />
<img src="https://imgur.com/37huEww.png" height="80%" width="80%" alt=""/>
<br />
<br />
</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
