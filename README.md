![1547808004624](https://github.com/user-attachments/assets/e70f6f7d-f667-4b45-9315-e53bf8e9bed6)

<br>


# 🚀 Getting Started

Navigate to the Azure Portal and sign in (create an account and start a subscription if needed).

On the Home screen, click "Rescource groups".

<img width="856" alt="Virtual Pic 5" src="https://github.com/user-attachments/assets/b1e9ab72-1a59-43ea-a0e6-3ecb2aefc69c" />
 <br>

Once in that section, click "+Create".

![image](https://github.com/user-attachments/assets/da2b67f3-1f94-4a65-9bd9-021c15fbeb18)<br>

Pick the appropriate subscription and make sure to create a resource name. It can be anything but the name cannot be spaced apart. Region can be anywhere but for this example, we will use "East US 2".

![image](https://github.com/user-attachments/assets/68775702-fa44-44c2-a05a-3d4959aaf08a)

Afterwards, we will skip "Tags" and go to "Review + create" and click the create button.

![image](https://github.com/user-attachments/assets/dcc8d81e-8da2-4126-a61b-57649e1c9db2)

Once created, the new resource group will be shown in the Resource group main screen. We will click on the home page so the Virtual Machine can be created. 

![image](https://github.com/user-attachments/assets/2237ce36-8dc5-4f7c-a3c0-42c475443fb4)

On the home page, click Virtual Machines. When on that page, click "+Create" and choose "Azure Virtual Machine".

![image](https://github.com/user-attachments/assets/4318d6d0-887e-4b8e-a6d8-5463f9606007)

# ⚙️ Settings Configuration
These next steps will show the settings used to create the virtual machine.

### Basics Tab
> **Subscription**

Choose the appriopriate subscription.

> **Resource Group**

Resource group have to be the same name created as shown in the previous steps "Pick-a-name-of-your-choosing".

> **Virtual machine name**

Virtual name can be anything. For this setup, I have simply chosen "Virtual1".

> **Region**

Region will have to be the same as created in Resource Groups. This one is "East US 2".

> **Availability options**

Leave as is.

> **Security type**

Leave as is.

> **Image**

Choose "Windows 10 Pro, version 22H2 - x64 Gen2(free services eligible)`".

> **VM Architecture**

Choose x64.

> **Size**

Choose "Standard_D2as_v4 - 2 vcpus, 8 GiB memory ($70.08/month)"


> **Username & Password**

Username and Password can of course be anything you want, just make sure that the password creation follows the standards. To be transparent, I simply used Password123! though it isn't ideal in a real world setting.
![image](https://github.com/user-attachments/assets/174ca3bc-f8e8-43b3-9a6c-efba9d7e2992)


> **Licensing**

Please do not forget to check the little checkbox or else you will not be able to create the VM.

![image](https://github.com/user-attachments/assets/f545b7b0-2684-47ee-a7d2-72cfb92065bf)


For this basic tutorial, we will leave the rest of the sections as it is and click "Review + create".

![image](https://github.com/user-attachments/assets/bf742e9d-9a92-47ef-aee8-4b78bd9f0f1d)

After clicking the create button, it will take a few minutes for the VM to deploy.

![image](https://github.com/user-attachments/assets/58298475-0d6a-4f9b-8201-e03de824af99)


# 🖥️ Accessing the Virtual Machine Remotely
On the Azure Portal homepage, click on the Virtual Machine name and copy the IP Address as shown below:

![image](https://github.com/user-attachments/assets/29e210c2-d8f8-42fd-9cd0-7dfdb3013077)


![image](https://github.com/user-attachments/assets/dc8e6041-ed0f-4792-8566-230762c5ab6e)

On Windows:

For simplicity, type Remote Desktop Connection in the search box and open it.

![Screenshot (1)](https://github.com/user-attachments/assets/b9cce0a0-e887-40ff-8da1-650c3e0f387e)


In the **Computer:** field, enter the public IPv4 address of the virtual machine. Username should be the same name created in Azure. Click Connect.

![image](https://github.com/user-attachments/assets/e7ede587-be0d-4569-bf4c-0f484c838985)


Enter the password that was set up earlier during the creation of the Azure virtual machine. 

![image](https://github.com/user-attachments/assets/0730f6fe-3c54-4a32-a608-9e3d987abf14)


If there is an error validating the remote computer's certificate, this can be dismisssed by clicking Yes.

![image](https://github.com/user-attachments/assets/679ec4dd-b3b0-4eff-9812-4912787d6fde)


Connect to the virtual machine and wait for the login process to complete. (This is the best picture that was obtained for this virtual machine).

![image](https://github.com/user-attachments/assets/9746d003-a56f-4f34-a79a-bdc0cc9bbfc1)

🎉Congrats! You have successfully created your Virtual Machine!

#  Deleting or Stopping the Virtual Machine
If you do not want to incur cost on the Virtual Machine, you can either click Stop from the Virtual Machine menu or click Delete and follow the correct steps for removal.

![image](https://github.com/user-attachments/assets/09e4441a-fba3-410d-b9dd-ffe8d9777558)

