# Azure Windows Server VM Lab

This project demonstrates how to deploy a Windows Server 2019 virtual machine using the Azure Free Tier, install IIS (web server), and make it accessible publicly with proper security rules and backup.

## 🔧 Technologies Used
- Microsoft Azure
- Windows Server 2019 Datacenter
- IIS Web Server
- PowerShell
- Azure Resource Groups, NSGs, Snapshots

## ✅ What Was Done
- Deployed VM using B1s size in Azure (free tier)
- Installed IIS on Windows Server
- Allowed port 80 (HTTP) in NSG for public access
- Configured auto-shutdown to avoid charges
- Created a snapshot as a full backup of the VM

## 📸 Screenshots
- IIS default page
- Azure VM Overview
- NSG HTTP Rule
- Snapshot screen


All screenshots are available in the `/screenshots` folder for reference.


## 📁 Project Structure

azure-windows-vm-lab/ ├── README.md # Main documentation for the project ├── notes.txt # Step-by-step setup notes and commands used └── screenshots/ # Visual evidence of the deployment ├── iis-page.png ├── vm-overview.png ├── nsg-rule-http.png ├── snapshot-created.png



## 📌 Notes
This lab was built to simulate a basic Azure System Administrator task flow and can be used as a foundation for further hands-on labs.
