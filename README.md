<h1>Alouima - OsTicket Install </h1>


<h2>Description</h2>
The mission is to create a Microsoft Azure virtual machine specifically configured to host osTicket, a widely used open-source support ticketing system. This setup included getting the steps from "Lab Checklist: osTicket Setup" storage resources and configuring the operating system for compatibility. The osTicket application was configured to enable seamless ticket submission, tracking, and management, integrating features such as email piping, customizable workflows, and detailed reporting tools. 


<h2>Languages and Utilities Used</h2>

- <b>Virtual Machine</b> 
- <b>Remote Desktop</b>

<h2>Environments Used </h2>

- <b>Windows 10</b> (4 vCPUs)
- <b>Azura</b>
  
<h2>Step by Step</h2>

<p align="center">
Launch Azura and Create a Virtual Machine: <br/>
<img <img width="1680" alt="Screenshot 2024-12-28 at 8 23 27 PM" src="https://github.com/user-attachments/assets/2e959e9a-525e-41b8-b1be-18883d6fb8ca" />
/>
<br />
<br />
Log into the VM with Remote Desktop
:  <br/>
<img <img width="1680" alt="Screenshot 2024-12-28 at 8 30 56 PM" src="https://github.com/user-attachments/assets/2354b045-6305-4a1b-ae6a-9104ca1d4e73" />
 />
/>
<br />
<br />
Install / Enable IIS in Windows WITH CGI: <br/>
<img <img width="1680" alt="Screenshot 2024-12-28 at 8 43 41 PM" src="https://github.com/user-attachments/assets/0f92122e-af5b-4a57-a2c4-c4c08cfe0909" />
 />
/>
<br />
<br />
Register PHP Manager for IIS:  <br/>
<img <img width="1680" alt="Screenshot 2024-12-28 at 8 52 31 PM" src="https://github.com/user-attachments/assets/48c27927-9b45-475f-ac04-592b33e66c10" />
/>
<br />
<br />
 install MySQL 5.5.62 :  <br/>
<img <img width="1680" alt="Screenshot 2024-12-28 at 8 51 11 PM" src="https://github.com/user-attachments/assets/037b79f8-c431-4ade-8b24-b1a62d6b7af1" />
/>
<br />
<br />
Reload PHP within IIS:  <br/>
<img <img width="1680" alt="Screenshot 2024-12-28 at 11 45 31 PM" src="https://github.com/user-attachments/assets/feaa5db0-ae58-428c-b507-76b27f7d5eb3" />
 />
 />
<br />
<br />
Install osTicket v1.15.8 and change the name to "osTicket":  <br/>
<img <img width="1680" alt="Screenshot 2024-12-28 at 8 57 44 PM" src="https://github.com/user-attachments/assets/866b3314-1c4b-4ff9-816e-0bcfe9f4adbe" />
 />
/>
/>
Continue Setting up osTicket in the browser until you see "Congratulations :  <br/>
<img <img width="1680" alt="Screenshot 2024-12-28 at 9 15 52 PM" src="https://github.com/user-attachments/assets/4970c7e6-95e0-4545-8bd0-ef86e4dc39f7" />
 />
 />
<br />
<br />
/>
/>
