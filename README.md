<p align="center">
<img src="https://i.imgur.com/pU5A58S.png" alt="Microsoft Active Directory Logo"/>
</p>

<h1> Active Directory: User Generation </h1>


<p>Welcome to the "Active Directory User Generation" project. In this project, we'll create user accounts using a powershell script to populate our domain for future use in simulated scenarios. </p>

<h2>Prerequisites</h2>

- <a href="https://github.com/P-furtado/ad-azuresetup"> Preliminary Setup for Active Directory and Network Traffic Analysis between Azure VMs </a>
- <a href="https://github.com/P-furtado/ad_deployment_Config"> Active Directory Deployment and Configuration </a>

<h2>Key Objectives</h2>

<h4>User Creation</h4>

-  Create a number of users using a power shell script in order to populate our domain

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Active Directory Domain Services

<h2>Operating Systems Used </h2>

- Windows Server 2022
- Windows 10 (21H2)

<p><strong>.</strong></p>
<p><strong>.</strong></p>


<h1>User Creation</h1>

<h3>&#9312; Run PowerShell script</h3>
<p>First we will be using a Powershell script to generate a number of users for our Active Directory Domain. 
</p>

- Login to DC-01 as jane_admin
- Open PowerShell_ise as an administrator and paste the contents of the <a href="https://github.com/joshmadakor1/AD_PS/blob/master/Generate-Names-Create-Users.ps1"> script </a> and run it. 

<br>

<img width="821" alt="POWERSHELL" src="https://github-production-user-asset-6210df.s3.amazonaws.com/158519921/304274480-bdc4f2ad-cb4b-4509-83cf-c2c1ec8c4dfd.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIAVCODYLSA53PQK4ZA%2F20241217%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20241217T151231Z&X-Amz-Expires=300&X-Amz-Signature=02ac794a00ba3d977fe0a7d627f8d56674a3477ceed5d7f5d33254474157cbf2&X-Amz-SignedHeaders=host">

<p><strong>The script will generate a number of users with a combination of consonants and vowels so the names might be unusual. </strong> </p>

<p>
</p>
<p><strong>.</strong></p>
<p><strong>.</strong></p>
<p><strong>.</strong></p>

<p><strong>Once the script is done running, you can verify in Active Directory that the users have been created.</strong></p>

<img width="562" alt="USERS" src="https://github-production-user-asset-6210df.s3.amazonaws.com/158519921/304274690-07b77e8f-07a7-4048-a04b-9d623ddebfc2.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIAVCODYLSA53PQK4ZA%2F20241217%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20241217T151304Z&X-Amz-Expires=300&X-Amz-Signature=db626cadf352cfba83cd59c05f8fd83972e0cf55bc6457f8294d28958ab93eeb&X-Amz-SignedHeaders=host">


<h3>&#9313; Login as user </h3>

- Now you can try logging in as one of the users to further verify that the script has worked.
- Take note of the default password in the script (Password1)

<img width="335" alt="LOGIN" src="https://github-production-user-asset-6210df.s3.amazonaws.com/158519921/304274875-2cedd731-17ff-4595-869b-0111d5bc2f6f.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIAVCODYLSA53PQK4ZA%2F20241217%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20241217T151328Z&X-Amz-Expires=300&X-Amz-Signature=b066985be957885d0016117ec52d7185801f830dbf2719644bb6fae62afab8e4&X-Amz-SignedHeaders=host">


<h2> Final Thoughts </h2>

<p> In closing, the "Active Directory User Generation" project streamlines our user management process. Using a PowerShell script, we efficiently create user accounts, setting the stage for the next projects.</p>
