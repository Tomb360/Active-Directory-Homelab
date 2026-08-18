<h1>Basic Active Directory Homelab</h1>


<h2>Description</h2>
This project demonstrates the configuration of Active Directory on a virtual machine using Oracle VirtualBox. It involves setting up IP addressing, creating a domain administrator account, and automating new user creation with a PowerShell script. Upon completion, a small corporate network is simulated by connecting a device to the domain controller's DHCP server to obtain internet access.
<br />



<h2>Software Used </h2>

- <b>Oracle VirtualBox</b>
- <b>Windows Server 2019</b>
- <b>Windows 10 Pro<b>
- <b>Windows PowerShell</b>

<h2>Reference Video and Network Diagram</h2>

[Reference Video](https://www.youtube.com/watch?v=MHsI8hJmggI) 

<img src="https://github.com/user-attachments/assets/85cc288a-94e0-4d58-aa40-01e871bc0848" height=80% width=80%/>


<h2>Walkthrough:</h2>

<p align="center">
Creating and installing Windows Server 2019 VM: <br/>
<img src= "https://github.com/user-attachments/assets/85b18c42-ff29-4909-8bbd-72408cbee639" height="80%" width="80%"/>
 <img src= "https://github.com/user-attachments/assets/37c3ffa0-e2ce-4e76-ad68-5d729df93d41" height="80%" width="80%"/>
<br />
 
<p align="center">
 Installing guest additions for smoother performance
<br/>
<img src="https://github.com/user-attachments/assets/f61545a1-ffa2-41a5-a4f9-a8fd6f22c566" height=80% width=80%/>
<p align="center">
Renaming networks and PC<br />
<img src="https://github.com/user-attachments/assets/3b53fb75-9256-4805-ab01-8fcbdd67bf53" height=80% width=80%/>
<img src="https://github.com/user-attachments/assets/d5ea3ee4-13ce-4107-a3c6-2cb74f4ddffa" height=80% width=80%/>
 
<p align="center">
Ip settings for internal NIC<br />
<img src="https://github.com/user-attachments/assets/4fe29d62-049c-487c-b5b2-d5613bbdd2a8" height=80% width=80%/>
 
<p align="center">
Installing Active Directory Domain Services<br />
<img src="https://github.com/user-attachments/assets/7bf43688-d456-4c3e-92ae-9bd1f8cf3531" height=80% width=80%/>
<img src="https://github.com/user-attachments/assets/13ac814e-b77e-4533-ad10-fd33d8c8ad57" height=80% width=80%/>
<img src="https://github.com/user-attachments/assets/0b43bdcc-bf93-4e46-a925-c2d10acda486" height=80% width=80%/>
 
<p align="center">
"mydomain" login success<br />
<img src="https://github.com/user-attachments/assets/4e54297a-011c-47a8-a9e5-f75f388d345a" height=80% width=80%/>
 
<p align="center">
Creating Domain Admin account<br />
<img src="https://github.com/user-attachments/assets/16bad6cb-c26b-4719-a38f-a6c698c488ce" height=80% width=80%/>
 
<p align="center">
Admin setup<br />
<img src="https://github.com/user-attachments/assets/5be57476-37a0-476c-ab75-7c41b879cafa" height=80% width=80%/>
 
<p align="center">
Making user member of Domain Admins<br />
<img src="https://github.com/user-attachments/assets/c7585b77-327f-49dc-a7f5-9747cbc0fda5" height=80% width=80%/>
 
<p align="center">
Sign is a new Domain Admin account<br />
<img src="https://github.com/user-attachments/assets/ac6d8f97-0fcc-479a-9497-0c7a13098759" height=80% width=80%/>
 
<p align="center">
RAS/NAT installation<br />
<img src="https://github.com/user-attachments/assets/bf9e7fa4-c114-4f12-9cd6-0310310adfdd" height=80% width=80%/>
<img src="https://github.com/user-attachments/assets/c8e9bd59-9533-43cf-af8c-85424a423697" height=80% width=80%/>
 
<p align="center">
DHCP server creation<br />
<img src="https://github.com/user-attachments/assets/bfbc8c6b-c43f-4e05-a95f-070e4ddbe59c" height=80% width=80%/>
 
<p align="center">
DHCP config<br />
<img src="https://github.com/user-attachments/assets/e021c7cb-66a5-4d82-9902-91df04e27814" height=80% width=80%/>
 
<p align="center">
Setup complete<br />
<img src="https://github.com/user-attachments/assets/e8d636ad-8a75-4bee-9ef2-a536e23b1a82" height=80% width=80%/>
 
<p align="center">
Powershell script code<br />
<img src="https://github.com/user-attachments/assets/9bd177e4-79b8-4795-8540-c59d07ac83bc" height=80% width=80%/>
 
<p align="center">
Running script<br />
<img src="https://github.com/user-attachments/assets/b3adcc2b-fd43-4f98-884e-47b431a4fca8" height=80% width=80%/>
 
<p align="center">
Installing Windows 10 VM to simulate a corporate device<br />
<img src="https://github.com/user-attachments/assets/680e53bf-6fe8-418d-a344-b92911c9ff02" height=80% width=80%/>
 
<p align="center">
Internet access test on Win10 VM<br />
<img src="https://github.com/user-attachments/assets/326b90df-1c5a-4fa3-ba6a-67fa74d1b756" height=80% width=80%/>
 
<p align="center">
Adding new user to domain<br />
<img src="https://github.com/user-attachments/assets/2a7f92f7-2ddc-4686-9178-019f50892d4a" height=80% width=80%/>
 
<p align="center">
CLIENT 1 visible on Domain Controller<br />
<img src="https://github.com/user-attachments/assets/e3bdf829-b86e-4da3-bccd-f7cf1726f96b" height=80% width=80%/>
 
<p align="center">
CLIENT 1 visible is AD Clients and Computers<br />
<img src="https://github.com/user-attachments/assets/ccb6bf50-7625-44db-8b48-7e367a1efa9b" height=80% width=80%/>
 
<p align="center">
Successful sign-in on client 1 computer<br />
<img src="https://github.com/user-attachments/assets/9171f5be-0b70-4dde-bf7d-61768ab0e17b" height=80% width=80%/>



<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
