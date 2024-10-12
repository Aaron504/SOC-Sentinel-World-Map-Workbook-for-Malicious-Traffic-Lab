# SOC-Sentinel-World-Map-Workbook-for-Malicious-Traffic-Lab
<p align="center">

  ![Screenshot 2024-10-12 173634](https://github.com/user-attachments/assets/f462f9bf-11c3-439e-a537-4210a184f6f9)

</p>

In this lab, I created and configured four workbooks in Azure Sentinel to visualize malicious traffic from around the world targeting our resources. Using pre-built JSON files, I set up maps to display Windows RDP/SMB Authentication Failures, Linux SSH Authentication Failures, MS SQL Server Authentication Failures, and NSG Allowed Malicious Inbound Flows. These maps leverage the logs ingested into our Log Analytics Workspace, enabling us to monitor pre-existing attack patterns and visualize global malicious activity over the past 30 days. This lab demonstrates my ability to utilize Azure Sentinel for real-time security monitoring and threat detection.




<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Micorsoft Sentinel
- Log Analytics
- KQL (Kusto Query Language)
  

<h2>Operating Systems Used </h2>

- Windows Server 2022
- Windows 10 (21H2)

<h2>High-Level Deployment and Configuration Steps</h2>

- Step 1 - Use linux-ssh-auth-fail.json to create the “Linux SSH Authentication Failures” map
- Step 2 - Use mssql-auth-fail.json to create the “MS SQL Server Authentication Failures” map
- Step 3 - Use nsg-malicious-allowed-in.json to create the “NSG Allowed Malicious Inbound Flows” map
- Step 4 - Use windows-rdp-auth-fail.json to create the “Windows RDP/SMB Authentication Failures” map


<h2>Deployment and Configuration Steps</h2>

- Use linux-ssh-auth-fail.json to create the “Linux SSH Authentication Failures” map
![Screenshot 2024-10-12 180012](https://github.com/user-attachments/assets/90d27bec-c3d5-42c8-a45b-b630ed7155e8)

![Screenshot 2024-10-12 175425](https://github.com/user-attachments/assets/335a96c6-6c7d-4b44-a866-ec40062f885d)

- Use mssql-auth-fail.json to create the “MS SQL Server Authentication Failures” map

- Use nsg-malicious-allowed-in.json to create the “NSG Allowed Malicious Inbound Flows” map
![Screenshot 2024-10-12 180925](https://github.com/user-attachments/assets/a0b10ff9-140c-4d80-83a4-a48dd94da6fe)
![Screenshot 2024-10-12 181153](https://github.com/user-attachments/assets/6524ff43-a9ac-4a85-9b88-8fd31c092661)

- Use windows-rdp-auth-fail.json to create the “Windows RDP/SMB Authentication Failures” map
![Screenshot 2024-10-12 181628](https://github.com/user-attachments/assets/8c5cbeec-a2e2-4b7b-9b4c-2600f6b8f21f)
![image](https://github.com/user-attachments/assets/6e2ec2a8-585c-4380-8a0c-d613ac214659)







