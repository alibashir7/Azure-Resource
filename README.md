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
First, we will go to https://portal.azure.com and log in. Once logged in, you will arrive at the following page: Click on resource groups or search for it in the search bar if it doesn't appear for you. <br/>
<img src="https://github.com/alibashir7/Azure-Resource/assets/165006117/0d4eb025-30df-4465-b0be-795ce82c38c9.png" height="80%" width="80%" alt=""/>
<br />
<br />
Select create:  <br/>
<img src="https://github.com/alibashir7/Azure-Resource/assets/165006117/7e87f578-4241-4315-bde7-602738173d8e.png" height="80%" width="80%" alt=""/>
<br />
<br />
Next, we will name our resource group, then click review + create. <br/>
<img src="https://github.com/alibashir7/Azure-Resource/assets/165006117/f2007c28-90a5-46ef-9d15-e12d397b6251.png" height="80%" width="80%" alt=""/>
<br />
<br />
Then we will click create:  <br/>
<img src="https://github.com/alibashir7/Azure-Resource/assets/165006117/146aaf9e-cff3-42c0-8b61-9c5c3257d934.png" height="80%" width="80%" alt=""/>
<br />
<br />
You should now see the resource group you created in the portal.  <br/>
<img src="https://github.com/alibashir7/Azure-Resource/assets/165006117/6f7a204c-b5e0-4f38-a7b1-21523f0a29cb.png" height="80%" width="80%" alt=""/>
<br />
<br />
Next, we will go back to https://portal.azure.com and click on virtual machines. Once again, if you don't see it on your home page, search for it in the search bar.  <br/>
<img src="https://github.com/alibashir7/Azure-Resource/assets/165006117/aae1cf24-8e3c-4c41-b055-7fe98746ff87.png" height="80%" width="80%" alt=""/>
<br />
<br />
Click on create on the top left corner and select virtual machine.  <br/>
<img src="https://github.com/alibashir7/Azure-Resource/assets/165006117/a7670d5b-3542-484f-9263-5464aafb8e51.png" height="80%" width="80%" alt=""/>
<br />
<br />
We will select the resource group we created for the resource group selection. Next, follow the same selections I made for the following instance details. If you select a certain region and don't see the same options as me, try changing your regions until you have the same configurations as me.  <br/>
<img src="https://github.com/alibashir7/Azure-Resource/assets/165006117/d2795ad1-cb0b-402f-aab6-f3410a18e4fd.png" height="80%" width="80%" alt=""/>
<br />
<br />
Create a username and password that are unique to your VM, and make sure to have them saved somewhere. We will need it later. Click on the box next to licensing on the bottom left.  <br/>
<img src="https://github.com/alibashir7/Azure-Resource/assets/165006117/26a0ead3-e018-4a79-89a1-413fd5745b2c.png" height="80%" width="80%" alt=""/>
<br />
<br />
Select Standard SSD:  <br/>
<img src="https://imgur.com/Nlz1IH7.png" height="80%" width="80%" alt=""/>
<br />
<br />
The virtual network and subnets ahould automatically be created for you by Azure as seen in the following image. Then we will click create + review.  <br/>
<img src="https://imgur.com/XsogsFB.png" height="80%" width="80%" alt=""/>
<br />
<br />
You will see validation passed then we will click create:  <br/>
<img src="https://imgur.com/Z47z7Bq.png" height="80%" width="80%" alt=""/>
<br />
<br />
Azure will start the deployment process of the virtual machine. Be patient as this process could take a while.  <br/>
<img src="https://imgur.com/gtuhbEZ.png" height="80%" width="80%" alt=""/>
<br />
<br />
Once the deployment process is done, go back to https://portal.azure.com and click on virtual machines, and you should see the Windows 10 VM there.  <br/>
<img src="https://imgur.com/kT1PcsC.png" height="80%" width="80%" alt=""/>
<br />
<br />
Next, we will create a Windows Server 2019 VM. We will follow the same exact process, with the only difference being that we will select Windows Server 2019 for the image instead of Windows 10 Pro.  <br/>
<img src="https://github.com/alibashir7/Azure-Resource/assets/165006117/d5a23eee-631a-43fb-aa6d-36ba03a012a2.png" height="80%" width="80%" alt=""/>
<br />
<br />
<img src="https://github.com/alibashir7/Azure-Resource/assets/165006117/737d3d40-c162-4128-9e55-95492685e4ca.png" height="80%" width="80%" alt=""/>
<br />
<br />
<img src="https://github.com/alibashir7/Azure-Resource/assets/165006117/06de970c-4c85-4598-9be3-438394f014cf.png" height="80%" width="80%" alt=""/>
<br />
<br />
<img src="https://github.com/alibashir7/Azure-Resource/assets/165006117/71591138-0a05-4c09-a37d-d90e7f6ab197.png" height="80%" width="80%" alt=""/>
<br />
<br />
<img src="(https://github.com/alibashir7/Azure-Resource/assets/165006117/52fbdca9-8caf-48f5-9d37-df05d77cc5ae.png" height="80%" width="80%" alt=""/>
<br />
<br />
<img src="https://github.com/alibashir7/Azure-Resource/assets/165006117/be545958-d2c2-4f6e-8838-10543324d547.png" height="80%" width="80%" alt=""/>
<br />
<br />
<img src="https://github.com/alibashir7/Azure-Resource/assets/165006117/5b036481-b7d4-4230-b4ff-fc213b5dbb27.png" height="80%" width="80%" alt=""/>
<br />
<br />
We will go back to the virtual machine portal, and you should see both Windows 10 and Windows Server running. If it doesn't say running as the status, just be patient and refresh the screen after a minute or two. Next, will type in our Windows search bar remote desktop connection and open it.  <br/>
<img src="https://imgur.com/Hfz6AA0.png" height="80%" width="80%" alt=""/>
<br />
<br />
<img src="https://imgur.com/vPQWPzL.png" height="80%" width="80%" alt=""/>
<br />
<br />
Once a remote desktop connection is open, you will be prompted to enter an IP address. The public IP address of our virtual machines that is provided to us in the portal is what we will use. Then we will be prompted to enter our credentials to access the VM, so we will use the username and password we created when setting up the VM. Click more choices, then click Use a different account. Proceed to enter your VM username and password, then click OK. When the Windows security prompt is brought up, just click yes.  <br/>
<img src="https://imgur.com/8FHnEp4.png" height="80%" width="80%" alt=""/>
<br />
<br />
<img src="https://imgur.com/6jImcjf.png" height="80%" width="80%" alt=""/>
<br />
<br />
<img src="https://imgur.com/aRGiRrr.png" height="80%" width="80%" alt=""/>
<br />
<br />
Finally, our Windows 10 VM will open in the remote desktop interface, and we will be able to use it just like a normal computer. For the sake of this tutorial, we will shutdown the VM once we are logged into the Windows 10 home screen.  <br/>
<img src="https://imgur.com/3pWzpNa.png" height="80%" width="80%" alt=""/>
<br />
<br />
<img src="https://imgur.com/6hkvvpC.png" height="80%" width="80%" alt=""/>
<br />
<br />
<img src="https://imgur.com/JQKb76y.png" height="80%" width="80%" alt=""/>
<br />
<br />
<img src="https://imgur.com/OmEcWno.png" height="80%" width="80%" alt=""/>
<br />
<br />
Once our VM is shutdown, we will now stop it in Azure so we don't incur more costs for having it running. Once it's fully stopped, you should see Stopped (Deallocated) next to both VMs. Make sure to give it a minute or two for Azure to shutdown the VMs fully. Refresh your page until you see that it has been stopped. If you don't see Stopped (Deallocated) next to the VMs, just try the same steps again of clicking the box next to each VM and clicking stop in the top right-hand corner.  <br/>
<img src="https://imgur.com/CYA0qgU.png" height="80%" width="80%" alt=""/>
<br />
<br />
<img src="https://imgur.com/EX7xfHo.png" height="80%" width="80%" alt=""/>
<br />
<br />
In order to save on storage costs, we will now delete our resource groups, which in turn will delete all our VMs and anything associated with them. This is a good practice to get used to once you are done using your VMs in Azure. First, we will go back to the portal home page and click on the resource group icon. Next, we will select the virtual machine resource group. Then select delete resource group and confirm the resource group deletion by typing in the name of the resource group and selecting delete.  <br/>
<img src="https://imgur.com/Xg0uWsl.png" height="80%" width="80%" alt=""/>
<br />
<br />
<img src="https://imgur.com/dVikawK.png" height="80%" width="80%" alt=""/>
<br />
<br />
<img src="https://imgur.com/CnAtLid.png" height="80%" width="80%" alt=""/>
<br />
<br />
Go back to the resource group section, select NetworkWatcherRG, and follow the same steps to delete it. When everything is deleted, we can go back to the resource group and VM interface, and we will see that everything has been removed. <br/>
<img src="https://imgur.com/PqpxoD2.png" height="80%" width="80%" alt=""/>
<br />
<br />
<img src="https://imgur.com/Zjxvx9j.png" height="80%" width="80%" alt=""/>
<br />
<br />
<img src="https://imgur.com/f7gAeEi.png" height="80%" width="80%" alt=""/>
<br />
<br />
<img src="https://imgur.com/2Rla8XF.png" height="80%" width="80%" alt=""/>
<br />
<br />
<img src="https://imgur.com/nkRJtZK.png" height="80%" width="80%" alt=""/>
<br />
<br />
<h2>Conclusion </h2>
That concludes this lab. Now you should know how to create VMs and resource groups in Azure. I recommend trying everything done in this lab by yourself multiple times until it makes sense or you have a solid understanding of how it is done.  <br/>
<br />
Thank You! <br/>
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
