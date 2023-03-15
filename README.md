
<h1>Active Directory: Enabling an Administrator account on Windows 11</h1>



<h2>Description</h2>
In most organizantions, you may be required to enable an Administrator account on Windows before adding the PC to the Domain. In this lab, we will enable an Administrator account on a Windows 11 PC. 
<br />




<h2>Environments Used </h2>

- <b>Windows 11 Pro</b> 

<h2> Enabling an Administrator account on Windows 11 </h2>

<p align="center">
From your home screen, open File Explorer, right click This PC, and select Manage.<br/>
<img src="https://github.com/Rastallworth1/Enabling-an-Administrator-account-on-Windows-11/blob/main/Screenshot%201.png"/>
<br />


<br />
Now you should be in Computer Management. From here, select Local Users and Groups from the left side and select the sub-folder Users. You will also see a sub-folder called Groups, however we will be focusing on the Users folder for this lab.<br/>
<img src="https://github.com/Rastallworth1/Enabling-an-Administrator-account-on-Windows-11/blob/main/Screenshot%202.png"/>
<br />


<br />
You should notice all the accounts associated to the PC. Windows 11 comes with a built in Administrator account, however it’s not automatically enabled. A quick way to tell if an account is enabled is to check and see there is a down arrow to the left of the accounts name. If it is, the account is disabled. In the lab, you can see that all account except for the vboxuser is disabled <br/>
<img src="https://github.com/Rastallworth1/Enabling-an-Administrator-account-on-Windows-11/blob/main/Screenshot%203.png"/>
<br />


<br />
Now, right click on the Administrator account and select properties. Next, you will unselect account is disabled, click apply, and OK. You have the option of naming the account, however for this lab, we will leave it as Administrator. <br/>
<img src="https://github.com/Rastallworth1/Enabling-an-Administrator-account-on-Windows-11/blob/main/Screenshot%204%20pt%201.png"/>
<br />
<br />Once you've entered the necessary information, click the OK button to create the user (Reggie). 
<br/>




<br />
As you can see, there is no longer a down arrow next to Administrator, which verifies the account is enabled. You will also want to set a password for the Administrator account. You’ll do this by right clicking again and selecting set password. Next, you will see a pop-up, disregard this pop-up and just select proceed and set a new password.  <br/>
<img src="https://github.com/Rastallworth1/Active-Directory-Creating-Users/blob/main/slide%205.png"/>
<br />
<br/>
<img src="https://github.com/Rastallworth1/Active-Directory-Creating-Users/blob/main/slide%205.png"/>
<br />
<br/>
<img src="https://github.com/Rastallworth1/Active-Directory-Creating-Users/blob/main/slide%205.png"/>
<br />



  <br />
To verify the password has been successfully set, simply sign out, and once you go to log back in, you notice you have an option for an Administrator sign in. You can now use the Administrator sign in. Depending on your organization, you may have to go back in and follow the previous steps and delete or disable the normal user account. <br/>
<img src="https://github.com/Rastallworth1/Active-Directory-Creating-Users/blob/main/Slide%207%20top.png"/>
<br />





 
  
  


<br />
This was a simple Active Directory Home Lab / Tutorial thats demonstrates the proper steps to enable an Administrator account on a Windows 11 PC.<br/>
