# Managing Windows VMs Using Azure Bastion

## Objective

The project aimed to manage Windows Virtual Machines (VMs) using Azure Bastion. The goal was to securely connect to VMs without exposing them to the public internet by leveraging Azure Bastion, which provides seamless and secure RDP and SSH connectivity. This project demonstrated advanced skills in Azure resource management, VM provisioning, and secure remote access configuration.

### Skills Learned

- Provisioning Windows VMs: Creating and configuring Windows VMs in Azure.
- Configuring Azure Bastion: Setting up Azure Bastion for secure and seamless connectivity to VMs.
- Secure Remote Access: Implementing secure RDP access to VMs without public IP exposure.
- Resource Management: Managing Azure resources, including VMs, virtual networks, and Bastion hosts.
- Network Configuration: Setting up and managing virtual networks, subnets, and network security groups (NSGs) for secure connectivity.

### Tools Used

- Microsoft Azure: For provisioning and managing virtual machines and Bastion hosts.
- Azure Bastion: For secure remote access to VMs.
- Azure Portal: For configuring and managing all Azure resources.

### Outcome
This project successfully demonstrated the ability to manage Windows Virtual Machines using Azure Bastion, showcasing advanced skills in secure remote access, VM provisioning, and resource management. By leveraging Azure Bastion, the project ensured that VMs were securely accessible without exposing them to the public internet, aligning with best practices for secure and efficient virtual machine management in the cloud.

## Steps

Create a VM and edit the NIC settings 

<img width="759" alt="Screenshot 2024-05-14 at 9 19 22 PM" src="https://github.com/Hunter102002/Azure-Bastion-/assets/98543129/58b706f8-d4e9-433e-8e08-355f73f3924e">

Generate a Keypair and download the file

<img width="387" alt="Screenshot 2024-05-14 at 9 19 57 PM" src="https://github.com/Hunter102002/Azure-Bastion-/assets/98543129/36831980-70f4-4b67-966b-22ca6e3c9740">

Verify VM

<img width="1470" alt="Screenshot 2024-05-14 at 9 20 43 PM" src="https://github.com/Hunter102002/Azure-Bastion-/assets/98543129/12a0062f-a743-4df9-8ec9-6e57a2539130">

Create a Subnet

<img width="1186" alt="Screenshot 2024-05-14 at 9 23 19 PM" src="https://github.com/Hunter102002/Azure-Bastion-/assets/98543129/53b1e7e1-0be7-48c8-a8ce-eb28d4d79b0a">

Deploy Azure Bastion

<img width="727" alt="Screenshot 2024-05-14 at 9 24 02 PM" src="https://github.com/Hunter102002/Azure-Bastion-/assets/98543129/a04413f8-5127-4a5a-a509-f8ee687f64eb">

Connect to the Bastion

<img width="767" alt="Screenshot 2024-05-14 at 9 38 07 PM" src="https://github.com/Hunter102002/Azure-Bastion-/assets/98543129/649b1ddb-4265-47f2-8bc5-337683d43720">

Connect using the keyfile we saved from the VM

<img width="723" alt="Screenshot 2024-05-14 at 9 40 16 PM" src="https://github.com/Hunter102002/Azure-Bastion-/assets/98543129/8c8fc208-9159-4a6f-ba22-3c8bc7a23c10">

Verify connection

<img width="682" alt="Screenshot 2024-05-14 at 9 40 58 PM" src="https://github.com/Hunter102002/Azure-Bastion-/assets/98543129/318a8f5a-b590-4319-9c76-e34c1f4f6d7d">
