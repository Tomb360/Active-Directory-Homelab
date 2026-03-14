<h1>MS365 Admin Homelab</h1>


<h2>Description</h2>
A hands on project was completed using a Microsoft 365 homelab environment to practice core service desk tasks within the admin centre. Theses tasks will commonlly be seen in a typical user lifecycle from onboarding to offboarding.
<br />



<h2>Software Used </h2>

- Oracle VirtualBox
- Microsoft 365 admin center
- Microsoft Entra admin center


<h2>Walkthrough:</h2>

<p align="center">
Onboarding a new user<br/>
<p align="left">
Onboarding is the complete process of setting up a new starter, which includes creating the user account, assigning licences, and ensuring equipment works. For account setup this can be done in both the 365 center and the Entra Center. Entra has a many of the same features but with a focus on Users and Identities.


<p align="center">
Entra Tenant<br/>
<img src="https://cdn.discordapp.com/attachments/1480782649818615900/1482240676321296434/image.png?ex=69b63bb3&is=69b4ea33&hm=2c24ea2d599c64dbf1bbce7e09d82a91ad3035e4db3520a9cfd99227c8f3e119&" height="80%" width="80%"/>
<p align="center">
Entra Homepage<br/>
 
<img src="https://cdn.discordapp.com/attachments/1480782649818615900/1482241115875840161/image.png?ex=69b63c1c&is=69b4ea9c&hm=9185d278a410c4b294a9cef196bd473ea4a643f5279974fe672c0c08c7503e22&" height="80%" width="80%"/>

<p align="center">
Admin Center Homepage<br/>
<img src="https://cdn.discordapp.com/attachments/1480782649818615900/1482241779100156066/image.png?ex=69b63cba&is=69b4eb3a&hm=ef212a8905c1c1a4c5f16335e73efeb48cf899c5096972b9221b2a3a1bd91ee8&" height="80%" width="80%"/>

<p align="center">
New User Creation<br/>
 
<img src="https://cdn.discordapp.com/attachments/1480782649818615900/1482243008295337985/image.png?ex=69b63ddf&is=69b4ec5f&hm=73641ae457a5100c0f09e2f696be4e6b031b76cc0d76a94ab28bc5233205dbd2&" height="80%" width="80%"/>

Here I create a user named steve and can assign the relevant licences to the user. Location is also important to condsider due to data sovereignty laws.

<p align="center">
Role Based Access Control<br/>
<p align="left">
Understanding Role Based Access Control is important as it governs what a user can actually do once logged in. The analyst needs to know which roles correspond to which job functions to assign the correct permissions. This prevents a user from having too much or too little access. This can be done in Entra by navigating to the assigned roles of a user. In this example, Steve will manage SharePoint so I assigned the Sharepoint Admin role to the user.
<img src="https://cdn.discordapp.com/attachments/1480782649818615900/1482244338606936287/image.png?ex=69b63f1d&is=69b4ed9d&hm=f790658316991103cf2d2b2c1e15ec154d97df56f15ba1f99dc051a8e8f366bf&" height="80%" width="80%"/>
<img src="https://cdn.discordapp.com/attachments/1480782649818615900/1482244854372372631/image.png?ex=69b63f98&is=69b4ee18&hm=353b0295d142e9ba765ccb634c061eb882b76d4f44ba2a4bef418687ecb419c7&" height="80%" width="80%"/>

<p align="center">
Password Reset Request<br/>
<p align="left">
Admins can reset their own passwords, but a common request an end user will make is for a password reset. Once verifying the request, it is as simple as navigating to a key icon by the users name in 365 admin center. In this example I reset a password for user Lara Croft.

<img src="https://cdn.discordapp.com/attachments/1480782649818615900/1482247064988418151/image.png?ex=69b641a7&is=69b4f027&hm=6f911f25a95702df73e61802addc84fec76273f4159da453671efcf45f984aea&" height="80%" width="80%"/>

A temporary password can be auto created, or I can create my own. This may be a better option if I am direct communication with the user and can use an easily memorable phrase to login to their account, then be prompted to reset their password once access has been regained.

<img src="https://cdn.discordapp.com/attachments/1480782649818615900/1482247561569108100/image.png?ex=69b6421d&is=69b4f09d&hm=0c9167a4942361860a9d0033ec2267fd7bf9657cbddfad6cc17fe3b757bfcec6&" height="80%" width="80%"/>


<p align="center">
Offboarding steps<br/>

<p align="left">
 
Offboarding is just as critical as onboarding because it secures the business when someone leaves. It is vital to prevent unauthorised access and ensure that company data remains protected after an employee's departure. The first step would be to block sign-in from the Admin Center.
 
<img src="https://cdn.discordapp.com/attachments/1480782649818615900/1482251124340691067/image.png?ex=69b6456e&is=69b4f3ee&hm=c731c8cf5f897be60182d021bef34e0965011f14d5c981bf4979e728d13f52d0&" height="80%" width="80%"/>

Licenses must then be removed so the company isnt paying for any inactive users, this is done by simply clearing the checkboxes.
If there is any relevant data in the users mail needed for operations to continue, it can be turned into a shared mailbox for the relevent users to have access to. This could be requested by a manager if required.

<img src="https://cdn.discordapp.com/attachments/1480782649818615900/1482251202644148264/image.png?ex=69b64581&is=69b4f401&hm=f637e943cb619afa7c82468cde1ecdf40748ba687ad637e380d98344cbfb09e6&" height="80%" width="80%"/>

Finally the User account can be deleted. Deleted account data is held for 30 days before being deleted permanently.
<img src="https://cdn.discordapp.com/attachments/1480782649818615900/1482251458345828386/image.png?ex=69b645be&is=69b4f43e&hm=2903499348c9d3fc5853a726c6c1cc670c095c0b769a35d0ac63c7ccd3a9cdf8&" height="80%" width="80%"/>

<br />
 




<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
