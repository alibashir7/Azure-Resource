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
<img src="https://github.com/alibashir7/Azure-Resource/assets/165006117/71cadc54-6d1a-48c1-9672-2e45f370a033.png" height="80%" width="80%" alt=""/>
<br />
<br />
The virtual network and subnets ahould automatically be created for you by Azure as seen in the following image. Then we will click create + review.  <br/>
<img src="https://github.com/alibashir7/Azure-Resource/assets/165006117/0eda6aba-0452-41dc-9fb8-fb6aa80b6075.png" height="80%" width="80%" alt=""/>
<br />
<br />
You will see validation passed then we will click create:  <br/>
<img src="https://github.com/alibashir7/Azure-Resource/assets/165006117/018b6db5-8a63-4c16-970f-a7197061a1b3.png" height="80%" width="80%" alt=""/>
<br />
<br />
Azure will start the deployment process of the virtual machine. Be patient as this process could take a while.  <br/>
<img src="https://github.com/alibashir7/Azure-Resource/assets/165006117/ddc880aa-672d-4b57-863c-58e4b7183352.png" height="80%" width="80%" alt=""/>
<br />
<br />
Once the deployment process is done, go back to https://portal.azure.com and click on virtual machines, and you should see the Windows 10 VM there.  <br/>
<img src="https://github.com/alibashir7/Azure-Resource/assets/165006117/c85795d3-9c6e-402a-aa78-81d8afa7344a.png" height="80%" width="80%" alt=""/>
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
<img src="https://github.com/alibashir7/Azure-Resource/assets/165006117/f0128737-42f7-4de6-9c07-050ce4723538.png" height="80%" width="80%" alt=""/>
<br />
<br />
<img src="https://github.com/alibashir7/Azure-Resource/assets/165006117/ce3352d5-e4a2-47c1-b533-831c49201c84.png" height="80%" width="80%" alt=""/>
<br />
<br />
Once a remote desktop connection is open, you will be prompted to enter an IP address. The public IP address of our virtual machines that is provided to us in the portal is what we will use. Then we will be prompted to enter our credentials to access the VM, so we will use the username and password we created when setting up the VM. Click more choices, then click Use a different account. Proceed to enter your VM username and password, then click OK. When the Windows security prompt is brought up, just click yes.  <br/>
<img src="https://github.com/alibashir7/Azure-Resource/assets/165006117/9215a01a-03d2-411b-acf3-99c5bfc3fd65.png" height="80%" width="80%" alt=""/>
<br />
<br />
<img src="https://github.com/alibashir7/Azure-Resource/assets/165006117/88c93ace-40a9-4fe8-b222-d937e29952cf.png" height="80%" width="80%" alt=""/>
<br />
<br />
<img src="https://github.com/alibashir7/Azure-Resource/assets/165006117/94b3ae54-b816-4c20-b52a-5a170dff469c.png" height="80%" width="80%" alt=""/>
<br />
<br />
Finally, our Windows 10 VM will open in the remote desktop interface, and we will be able to use it just like a normal computer. For the sake of this tutorial, we will shutdown the VM once we are logged into the Windows 10 home screen.  <br/>
<img src="https://github.com/alibashir7/Azure-Resource/assets/165006117/9255ce92-f765-49f1-a5ea-1e21bc13dc90.png" height="80%" width="80%" alt=""/>
<br />
<br />
<img src="https://github.com/alibashir7/Azure-Resource/assets/165006117/5115f919-fd73-45d0-96e2-d4f9bd8c1f41.png" height="80%" width="80%" alt=""/>
<br />
<br />
<img src="https://github.com/alibashir7/Azure-Resource/assets/165006117/49c21621-889e-4f0f-b978-9479ac36c361.png" height="80%" width="80%" alt=""/>
<br />
<br />
<img src="https://github.com/alibashir7/Azure-Resource/assets/165006117/96aed981-5b0e-402d-a8d1-ea0e5e0a2c15.png" height="80%" width="80%" alt=""/>
<br />
<br />
Once our VM is shutdown, we will now stop it in Azure so we don't incur more costs for having it running. Once it's fully stopped, you should see Stopped (Deallocated) next to both VMs. Make sure to give it a minute or two for Azure to shutdown the VMs fully. Refresh your page until you see that it has been stopped. If you don't see Stopped (Deallocated) next to the VMs, just try the same steps again of clicking the box next to each VM and clicking stop in the top right-hand corner.  <br/>
<img src="https://github.com/alibashir7/Azure-Resource/assets/165006117/5175d58c-4a9d-4903-916f-ee1542f9a082.png" height="80%" width="80%" alt=""/>
<br />
<br />
<img src="https://github.com/alibashir7/Azure-Resource/assets/165006117/da28c440-595b-4fd4-a4d6-c9a35b8db994.png" height="80%" width="80%" alt=""/>
<br />
<br />
In order to save on storage costs, we will now delete our resource groups, which in turn will delete all our VMs and anything associated with them. This is a good practice to get used to once you are done using your VMs in Azure. First, we will go back to the portal home page and click on the resource group icon. Next, we will select the virtual machine resource group. Then select delete resource group and confirm the resource group deletion by typing in the name of the resource group and selecting delete.  <br/>
<img src="https://github.com/alibashir7/Azure-Resource/assets/165006117/c6ff6db8-0a7d-4b20-a12b-a3296d390b31.png" height="80%" width="80%" alt=""/>
<br />
<br />
<img src="https://github.com/alibashir7/Azure-Resource/assets/165006117/d8088f76-7780-4002-83e3-274f750ecceb.png" height="80%" width="80%" alt=""/>
<br />
<br />
<img src="(https://github.com/alibashir7/Azure-Resource/assets/165006117/c5463edf-cecf-4ad0-8085-22c20b5137a1.png" height="80%" width="80%" alt=""/>
<br />
<br />
 <img src="https://github.com/alibashir7/Azure-Resource/assets/165006117/9cc2a61f-cc3b-40ef-b463-ba6a0dd31fa9.png" height="80%" width="80%" alt=""/>
<br />
<br />
Go back to the resource group section, select NetworkWatcherRG, and follow the same steps to delete it. When everything is deleted, we can go back to the resource group and VM interface, and we will see that everything has been removed. <br/>
<img src="https://github.com/alibashir7/Azure-Resource/assets/165006117/d76ea68b-8b69-4ccd-82b7-800e231faa3f.png" height="80%" width="80%" alt=""/>
<br />
<br />
<img src="https://github.com/alibashir7/Azure-Resource/assets/165006117/ac095a19-a73f-4f9b-b1b1-ee542062a147.png" height="80%" width="80%" alt=""/>
<br />
<br />
<img src="https://github.com/alibashir7/Azure-Resource/assets/165006117/a233aef9-5e41-4d67-874d-fe3ccf44d38b.png" height="80%" width="80%" alt=""/>
<br />
<br />
<img src="https://github.com/alibashir7/Azure-Resource/assets/165006117/57311e54-3ace-49af-bd00-7153ce192fad.png" height="80%" width="80%" alt=""/>
<br />
<br />
<img src="https://github.com/alibashir7/Azure-Resource/assets/165006117/3e3f61bd-e0eb-40ba-970a-8e6243896534.png" height="80%" width="80%" alt=""/>
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
