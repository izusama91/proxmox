[Back to Main Page](README.md)

## Create Virtual Machine
Create a resource > Virtual machine > Create
<details>
  <summary>Example</summary>
  
  ![](images/create-a-vm.png)
</details>

Configure Basics:
| Setting | Value |
| :--- | :--- |
| **Resource group** | WireGuard |
| **Virtual machine name** | wgserver |
| **Region** | Malaysia West |
| **Image** | Debian 12 |
| **Size** | B1s |
| **Authentication type** | SSH public key |
| **Username** | wgadmin |
| **SSH public key source** | Generate new key pair |
| **SSH Key Type** | Ed25519 SSH Format |
| **Key pair name** | wgserver_key |
| **Public inbound port** | Allow selected ports |
| **Select inbound ports** | SSH (22) |
<details>
  <summary>Example</summary>
  
  ![](images/create-a-vm-basics.png)
</details>

Configure Disks:
| Setting | Value |
| :--- | :--- |
| **OS disk size** | Image default (30 GiB) |
| **OS disk type** | Standard SSD (LRS) |
<details>
  <summary>Example</summary>
  
  ![](images/create-a-vm-disks.png)
</details>

