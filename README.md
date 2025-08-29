# System Engineer Homelab

## Project: Set up Windows Server VM in Azure

This documentation explains step by step how to deploy and configure a Windows Server virtual machine in Microsoft Azure.

---

## Steps
1. Create a resource group.
2. Deploy a Windows Server virtual machine.
3. Configure networking and access.
4. installing roles and feautures
5. Test the connection.

---

## Screenshots
### Step 1: Create and configure a VM

During the creation process, additional configuration options such as availability zone, security type, and image selection were set.

![VM Creation 1](./images/Bild_2025-08-29_172434118.png)  
![VM Creation 2](./images/Bild_2025-08-29_173005125.png)


### Step 2: Deploy the VM

![VM Configuration](./images/Bild_2025-08-29_173714162.png)

Deploying bastion:
![VM Deploy](./images/Bild_2025-08-29_174612499.png)


### Step 3: Configure networking and access

Setting static Ip: 
![Configuration](./images/Bild_2025-08-29_175307868.png)

connect via baston:

![connection](images/Bild_2025-08-29_175819553.png)

![connected](images/Bild_2025-08-29_180308938.png)

Turning off service manager: 

![serviceoff](images/Bild_2025-08-29_180548337.png)


### Step 4: installing roles and feautures


