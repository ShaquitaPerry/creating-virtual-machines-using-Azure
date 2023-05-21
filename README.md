# Creating-virtual-machines-using-Azure
In this tutorial outlines, we will be creating a virtual machine using Microsoft Azure.

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)



First you will need to go to Microsoft Azure at portal.azure.com and create your account if you haven't done so already.

Next go to the home page, you will see a search bar at the top and you will need to search for virtual machine.
![image](https://github.com/ShaquitaPerry/creating-virtual-machines-using-Azure/assets/133075771/63ce01ab-abaa-4b95-a49f-6606e5232b80)

Second click the create button at the top left and push Azure virtual machine.
![image](https://github.com/ShaquitaPerry/creating-virtual-machines-using-Azure/assets/133075771/676a44ba-c75c-4717-90f0-3b6dd368bb1f)


Next you will have to fill out all the information for the project details. 

1.Subscription- Usually a subscription is made for you when you created your Microsodt Azure account.

2.Resource group (A container that holds related resources for an Azure solution. The resource group can include all the resources for the solution, or only those resources that you want to manage as a group. You decide how you want to allocate resources to resource groups based on what makes the most sense for your organization.)- You can use a resource group you have already created or you can create a new one.

3.Virtual machine name (Virtual machines in Azure have two distinct names: virtual machine name used as the Azure resource identifier, and in guest host name. When you create a VM in the portal, the same name is used for both the virtual machine name and the host name. The virtual machine name cannot be changed after the VM is created. You can change the host name when you log into the virtual machine.)- Name it whatever you please.

4. Region (Choose the Azure region that's right for you and your customers. Not all VM sizes are available in all regions)- Select your region.
  
5. Availability options and zone- You can keep these settings as default.

6. Image (The base operating system or application for the VM)- Choose the type of virtual machine you would like. For this project, we'll choose Windows.

![image](https://github.com/ShaquitaPerry/creating-virtual-machines-using-Azure/assets/133075771/99fccb29-87c2-4479-86ce-35fc1f69bbe4)

7. Size (a VM size to support the workload that you want to run. The size that you choose then determines factors such as processing power, memory, and storage capacity. Azure offers a wide variety of sizes to support many types of uses. Azure charges an hourly price based on the VM's size and operating system)- For training purposes we'll choose Standard_B1s - 1 vcpu, 1 GiB memory

8. Authentication type- click password and a field will pop up for you to type in a username and password. (Remember these credentials as you will need it to log into your virtual machine.

9. Public inbound ports- Allow selected ports

![image](https://github.com/ShaquitaPerry/creating-virtual-machines-using-Azure/assets/133075771/cebf41be-017f-413e-8f3c-a8acb7b926b3)


Next at the bottom, click Review + create.
![image](https://github.com/ShaquitaPerry/creating-virtual-machines-using-Azure/assets/133075771/a7bdfd77-9670-49d2-ab3c-7d54479330b8)

Finally you will be taken to a page, where you can review all the information you enter to ensure it's correct. To the bottom left, click create.
![image](https://github.com/ShaquitaPerry/creating-virtual-machines-using-Azure/assets/133075771/ffa41e8d-9840-4cc7-ac22-fe38a2796050)

You have now created your own virtual machine :) 

Thanks for taking the time out to view my project!!
