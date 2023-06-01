# Azure_Intro-Mac-OS

<p align="center">
<img src="https://i.imgur.com/7AUG74j.png" height="40%" width="40%" alt="Microsoft Azure Logo"/>
</p>

<h1>Create an Azure Account and Deploy a Virtual Machine</h1>
In this guide, we will explore Microsoft Azure, a comprehensive cloud computing platform offering a wide array of products and services. You will learn how to create an account, navigate the portal effectively, and master the process of creating a virtual machine.

<h2>Environments and Technologies Used</h2>

- Microsoft Azure
- Microsoft Remote Desktop (macOS) for virtual machines

<h2>Configuration Steps</h2>

- Step 1: Create Azure Account
- Step 2: Azure portal and resource group
- Step 3: Create a virtual machine
- Step 4: Connect to virtual machine using Microsoft Remote Desktop on macOS

<h3>Step 1: Create Azure Account</h3>
To begin, the initial step involves setting up your own Azure account. When creating an account, you will be delighted to know that you receive a generous $200 worth of free credit, valid for an entire month, but only till the date, as soon as it passes you will need to pay as you go.

<br>
<br>

Create an Azure account [here](https://azure.microsoft.com/en-us/free/).

<p align="center">
<img src="https://i.imgur.com/8NgUUZu.png" height="80%" width="80%" alt="Azure Free Account"/>
  
<p align="center">
<img src="https://i.imgur.com/mSLAKSQ.png" height="80%" width="80%" alt="Azure Free Services"/>
</p>

In this guide, we will walk you through the process of creating an account on Microsoft Azure. By signing up, you will be eligible to receive $200 of free credit for a month. We will cover the steps to create your account, explore the Azure portal, and demonstrate how to create a virtual machine.

<h3>Step 2: Azure portal and resource groups</h3>

With your account successfully created, let's delve into navigating the Azure portal. The portal serves as the central hub where you can access various products, resources, and effectively manage your subscriptions. Designed with user-friendliness in mind, the portal offers an intuitive interface to streamline your Azure experience.

The portal is [here](https://www.portal.azure.com).

<p align="center">
<img src="https://i.imgur.com/8JnxniW.png" height="80%" width="80%" alt="Azure Portal with RG Arrow"/>
</p>

To utilize Azure services, it is necessary to create a resource group. Resource groups act as containers for storing all your Azure resources. In this example, we will guide you through the deployment of a Windows 10 virtual machine, while also demonstrating the creation of a resource group.

<p align="center">
<img src="https://i.imgur.com/x5P8pDQ.png" height="80%" width="80%" alt="Azure Resource Groups with circle"/>
</p>

When ready, click create resource groups. From there, you will need to name your resource group and select the region. The region will determine which Azure data center will be utilize. (US) West 3 was chosen for this example. Click "Review + Create" once finished

<p align="center">
<img src="https://i.imgur.com/4ZY0Twp.png" height="80%" width="80%" alt="Create Azure Resource Groups"/>
</p>

<h3>Step 3: Create a virtual machine</h3>
Now, let's proceed to create a virtual machine. Within the Azure portal, navigate to the virtual machine section and click on "Create." This will take you to the create virtual machine menu. Follow the instructions provided, ensuring to fill out all the required fields marked with a red asterisk, such as resource group and name. You can disregard the other tabs like disks and networking, as they will be prepopulated for you. Remember to note down the username and password you set. Once you've completed these steps, your virtual machine will be visible within your resource group.

<p align="center">
<img src="https://i.imgur.com/XC53r2o.png" height="80%" width="80%" alt="Virtual Machine Menu with arrow"/>
</p>

<p align="center">
<img src="https://i.imgur.com/a0OIYax.png" height="80%" width="80%" alt="Create Virtual Machine"/>
</p>

<h3>Step 4: Connect to virtual machine using Microsoft Remote Desktop (RDP)</h3>
The final step to this process is accessing the virtual machine using Microsoft Remote Desktop. If you are a macOS user, you have to download the application in the App Store. 

<p align="center">
<img src="https://i.imgur.com/pp1yQTE.png" height="80%" width="80%" alt="Microsoft Remote Desktop"/>
</p>

In order to connect to the virtual machine, you will need the public IP address. You can find this on the right hand side of this menu.

<p align="center">
<img src="https://i.imgur.com/gT6F62H.png" height="80%" width="80%" alt="SampleVM menu with arrow and circle"/>
</p>

Once Microsoft Remote Desktop is downloaded, open the application. Click add PC. Copy and paste the public IP address of the virtual machine that was created when prompted. Type in the username and password the click connect. 

<p align="center">
<img src="https://i.imgur.com/WcRdlX3.png" height="80%" width="80%" alt="Microsoft Remote Desktop 1"/>
</p>

<p align="center">
<img src="https://i.imgur.com/4IKJFik.png" height="80%" width="80%" alt="Windows 10 VM"/>
</p>
