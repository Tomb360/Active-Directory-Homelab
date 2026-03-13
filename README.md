<h1>Basic Active Directory Homelab</h1>


<h2>Description</h2>
This project demonstrates the configuration of Active Directory on a virtual machine using Oracle VirtualBox. It involves setting up IP addressing, creating a domain administrator account, and automating new user creation with a PowerShell script. Upon completion, a small corporate network is simulated by connecting a device to the domain controller's DHCP server to obtain internet access.
<br />



<h2>Software Used </h2>

- Oracle VirtualBox
- <b>Windows Server 2019</b>
- <b>Windows 10 Pro<b>
- <b>PowerShell</b>

<h2>Reference Video and Network Diagram</h2>

[Reference Video](https://www.youtube.com/watch?v=MHsI8hJmggI) 

<img src="https://cdn.discordapp.com/attachments/1480598419302125768/1480606862876606617/image.png?ex=69b4e758&is=69b395d8&hm=ed32a5258c700393567acb6f9039088bf7d381d6d4ea0710b7b4ab1e8e00359f&" height=80% width=80%/>


<h2>Walkthrough:</h2>

<p align="center">
Creating and installing Windows Server 2019 VM: <br/>
<img src="https://cdn.discordapp.com/attachments/1480598419302125768/1480598437840814221/image.png?ex=69b0423f&is=69aef0bf&hm=2e2d1bf771319d3e7964692502b10fb597462a26a524f7b3eb319f1e168adf6c&" height="80%" width="80%"/>
 <img src= "https://cdn.discordapp.com/attachments/1480598419302125768/1480602639552221195/image.png?ex=69b4e369&is=69b391e9&hm=5f83b4102ebc401c3c72ab329f1ec58bc9be742a9e8f667e79866f808b09148c&" height="80%" width="80%"/>
<br />
 
<p align="center">
 Installing guest additions for smoother performance
<br/>
<img src="https://cdn.discordapp.com/attachments/1480598419302125768/1480605706481696952/image.png?ex=69b4e644&is=69b394c4&hm=49426553731b4d447b08e6a824dd6d4abef23cff16fed018ff0cae4dd0c08ef3&" height=80% width=80%/>
<p align="center">
Renaming networks and PC<br />
<img src="https://cdn.discordapp.com/attachments/1480598419302125768/1480607744208797776/image.png?ex=69b4e82a&is=69b396aa&hm=271f7ecfc3db54bb66e7dc15f7b7c3be9f26e67afae3f9feaed20e861985597a&" height=80% width=80%/>
<img src="https://cdn.discordapp.com/attachments/1480598419302125768/1480607984848474123/image.png?ex=69b4e863&is=69b396e3&hm=242dc9b6c3c234604c2fceaee6e3222de445aced956ec0a9b1e671a0bd3f88db&" height=80% width=80%/>
 
<p align="center">
Ip settings for internal NIC<br />
<img src="https://cdn.discordapp.com/attachments/1480598419302125768/1480609126483759159/image.png?ex=69b4e974&is=69b397f4&hm=362bbd6452dd123640ff4e9609d66e11f3c16cc858cec97e2c01330dddea45be&" height=80% width=80%/>
 
<p align="center">
Installing Active Directory Domain Services<br />
<img src="https://cdn.discordapp.com/attachments/1480598419302125768/1480609604802187325/image.png?ex=69b4e9e6&is=69b39866&hm=1de35d10be15afe79de770054223b2514bac28b23996380b08390498a5cc3a4d&" height=80% width=80%/>
<img src="https://cdn.discordapp.com/attachments/1480598419302125768/1480609728781488288/image.png?ex=69b4ea03&is=69b39883&hm=c9eefda52f5cc3133f34ab8b8b71e674cc1c5f1145ee3fbf49804153bd21ed1d&" height=80% width=80%/>
<img src="https://cdn.discordapp.com/attachments/1480598419302125768/1480612776060649534/image.png?ex=69b4ecda&is=69b39b5a&hm=7174c7429cf09f62e05858981d8c0a9ba3a36dc4cd00c8cd919b6b415439948c&" height=80% width=80%/>
 
<p align="center">
"mydomain" login success<br />
<img src="https://cdn.discordapp.com/attachments/1480598419302125768/1480615663377846474/image.png?ex=69b4ef8a&is=69b39e0a&hm=153c6951f0a528d2cde36aced21271e60368112da01d82a7418395c9dc56bfb5&" height=80% width=80%/>
 
<p align="center">
Creating Domain Admin account<br />
<img src="https://cdn.discordapp.com/attachments/1480598419302125768/1480616214232563822/image.png?ex=69b4f00d&is=69b39e8d&hm=994127856ba2c1f7361e51aaf9251ae4e3b31102a184b96abdf74cbbf922c739&" height=80% width=80%/>
 
<p align="center">
Admin setup<br />
<img src="https://cdn.discordapp.com/attachments/1480598419302125768/1480616713799078000/image.png?ex=69b4f085&is=69b39f05&hm=ee74c14dce0c86bc9c05fde37aec41964aeb7a61edc7182dd5bf69ab28c18fbe&" height=80% width=80%/>
 
<p align="center">
Making user member of Domain Admins<br />
<img src="https://cdn.discordapp.com/attachments/1480598419302125768/1480617230277541888/image.png?ex=69b4f100&is=69b39f80&hm=3ced6d9793251c20a1975648b9c26f1e70b2c07d8ec35f194ece85a8327e13ae&" height=80% width=80%/>
 
<p align="center">
Sign is a new Domain Admin account<br />
<img src="https://cdn.discordapp.com/attachments/1480598419302125768/1480619140212461760/image.png?ex=69b4f2c7&is=69b3a147&hm=22156ffd9b364b8ebe9a28ce73064130c6a8c9ef475248af0a45865f5078ba80&" height=80% width=80%/>
 
<p align="center">
RAS/NAT installation<br />
<img src="https://cdn.discordapp.com/attachments/1480598419302125768/1480619723149279424/image.png?ex=69b4f352&is=69b3a1d2&hm=6ff58d63b1656af669bc820139cc23fdf319e7e57439d104f26574c51379d524&" height=80% width=80%/>
<img src="https://cdn.discordapp.com/attachments/1480598419302125768/1480622140603629608/image.png?ex=69b4f592&is=69b3a412&hm=9a22a6f38c5549de6df54a7ec2d1b9cb73c40d1621152cd49cf94dd193c69b91&" height=80% width=80%/>
 
<p align="center">
DHCP server creation<br />
<img src="https://cdn.discordapp.com/attachments/1480598419302125768/1480691385458757722/image.png?ex=69b48d50&is=69b33bd0&hm=0715090d30db2a51f2c792a099036b73e53c56a1f549a55c6d5bf97852f60a28&" height=80% width=80%/>
 
<p align="center">
DHCP config<br />
<img src="https://cdn.discordapp.com/attachments/1480598419302125768/1480693104297119896/image.png?ex=69b48eea&is=69b33d6a&hm=8a7faf5db30ea1e598977325030e3dc7ea3490bf6a21aca9fb00b2fb0a3a6d73&" height=80% width=80%/>
 
<p align="center">
Setup complete<br />
<img src="https://cdn.discordapp.com/attachments/1480598419302125768/1480694243591852133/image.png?ex=69b48ff9&is=69b33e79&hm=274dd55fac2ea46ff97b1674d88747a4704ddb5626184446b1b871364e984151&" height=80% width=80%/>
 
<p align="center">
Powershell script code<br />
<img src="https://cdn.discordapp.com/attachments/1480598419302125768/1480695210567794861/image.png?ex=69b490e0&is=69b33f60&hm=a329daabe778d5a2f49b26b3e325227868a662e89425faea5f157c288a94522a&" height=80% width=80%/>
 
<p align="center">
Running script<br />
<img src="https://cdn.discordapp.com/attachments/1480598419302125768/1480695958592422110/image.png?ex=69b49192&is=69b34012&hm=a30f502570a396b97e487bad569227ef8abc0090752399a290885ed70eab9eb7&" height=80% width=80%/>
 
<p align="center">
Installing Windows 10 VM to simulate a corporate device<br />
<img src="https://cdn.discordapp.com/attachments/1480598419302125768/1480712416429080727/image.png?ex=69b4a0e6&is=69b34f66&hm=a6203caada15009737381523b09c45c732af4c685467049ba7ef1a9429a3c055&" height=80% width=80%/>
 
<p align="center">
Internet access test on Win10 VM<br />
<img src="https://cdn.discordapp.com/attachments/1480598419302125768/1480716670489198642/image.png?ex=69b4a4dc&is=69b3535c&hm=f9721dcdf02e22b2519caad1983e3a25a6c7693b4c32726eb84bc7f208bf7501&" height=80% width=80%/>
 
<p align="center">
Adding new user to domain<br />
<img src="https://cdn.discordapp.com/attachments/1480598419302125768/1480717398293352618/image.png?ex=69b4a58a&is=69b3540a&hm=2be4d0e8c2be88bdcc0f500a2978825f85edd72bd2fd9cf814b2346cce0b8176&" height=80% width=80%/>
 
<p align="center">
CLIENT 1 visible on Domain Controller<br />
<img src="https://cdn.discordapp.com/attachments/1480598419302125768/1480717945067012301/image.png?ex=69b4a60c&is=69b3548c&hm=5c70878b3ed7ea68965c77c088684101323bcd5b301e7b1bbf7b26488ad56543&" height=80% width=80%/>
 
<p align="center">
CLIENT 1 visible is AD Clients and Computers<br />
<img src="https://cdn.discordapp.com/attachments/1480598419302125768/1480718304980242502/image.png?ex=69b4a662&is=69b354e2&hm=aa669f68e2223975141e210e6da96133c1a27d849395e75eec32736bfdcd6aab&" height=80% width=80%/>
 
<p align="center">
Successful sign-in on client 1 computer<br />
<img src="https://cdn.discordapp.com/attachments/1480598419302125768/1480718996167983145/image.png?ex=69b4a707&is=69b35587&hm=128f00ca1a3ce067ca9fd28e8ea7ad293e79265827efc5c17a8757661ee864e0&" height=80% width=80%/>



<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
