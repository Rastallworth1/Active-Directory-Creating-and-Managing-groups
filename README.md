<h1>Active Directory: Creating and Managing Groups</h1>



<h2>Description</h2>
Active Directory is a core tool for System Administrators that need to manage Windows machines. In this project we created a new new group and added that group to a larger group. 
<br />




<h2>Environments Used </h2>

- <b>Windows Server 19</b> 

<h2>Creating a new group:</h2>

<p align="center">
Now let’s add a new group. If you browse through the existing groups, you will see that there's a group called Developers and a group called Java Developers. We now want to add an additional group, called C Plus Developers. We will add the new group to the Developers group.<br/>
<img src="https://github.com/Rastallworth1/Active-Directory-Creating-and-Managing-groups/blob/main/slide%201.jpg"/>
<br />
<br />
To create a new group, use the same menu that you used for creating a new user, but this time select the new Group option.<br/>
<br/>
<img src="https://github.com/Rastallworth1/Active-Directory-Creating-and-Managing-groups/blob/main/slide%201%20bottom.jpg"/>
<br />


<br />
As you can see below, a similar window to the one that we saw before has appeared, but this time it requires the data for the Group rather than the user.<br/>
<img src="https://github.com/Rastallworth1/Active-Directory-Creating-and-Managing-groups/blob/main/slide%202.jpg"/>
<br />
<br />
Similar to creating User accounts, only the block with the red Asterisks is required.  You can add additional information in the Description and Notes if desired. Once you are done, click OK to have the group created.<br/>



<br />
Now we want to add the C Plus Developers group to the Developers group that already exists. We can do this by scrolling down to the new entry and then right clicking on the entry in the list and selecting the Add to another group entry.. <br/>
<img src="https://github.com/Rastallworth1/Active-Directory-Creating-Users/blob/main/Slide%203.png"/>
<br />


<br />
This will open a new window that lets you fill in a number of fields related to the new user. There are numerous fields available, but only a few are mandatory, which are marked with a read asterisk. You can leave the rest empty. The user that we are creating is called Reggie, with their username being also Reggie.<br/>
<img src="https://github.com/Rastallworth1/Active-Directory-Creating-Users/blob/main/slide%204.png"/>
<br />
<br />Once you've entered the necessary information, click the OK button to create the user (Reggie). 
<br/>




<br />
Once you click on the newly created account, you will see that where it displays the name of the user, the system says Reggie (Disabled). This is a problem, but it can be easily fixed by enabling it. <br/>
<img src="https://github.com/Rastallworth1/Active-Directory-Creating-Users/blob/main/slide%205.png"/>
<br />

  <br />
Lets try to enable Reggie's account. What happens if you right click on the entry and try to Enable it? The system will not enable an account unless you have a strong password that meets your organizations guidelines. In this case, the password is weak because we haven't set it. Obviously, an empty password is not a strong password. <br/>
<img src="https://github.com/Rastallworth1/Active-Directory-Creating-Users/blob/main/Slide%206%20Top.png"/>
<br />
<br/>
<img src="https://github.com/Rastallworth1/Active-Directory-Creating-Users/blob/main/slide%206%20bottom.png"/>
<br />


  <br />
You can set a password using the Reset password menu option. This will allow the administator to enable the account. Another good practice is to have the User change the password at next logon. This can be done by selecting the change password at next logon option, this will ensure that the user will change their password when they log in. The goal here is to ensure that only the user knows their password and not the System Administrator. <br/>
<img src="https://github.com/Rastallworth1/Active-Directory-Creating-Users/blob/main/Slide%207%20top.png"/>
<br />
<br/>
<img src="https://github.com/Rastallworth1/Active-Directory-Creating-Users/blob/main/slide%207%20bottom.png"/>
<br />

  
<br />
Once you've set a strong password, you can retry enabling the account. This time it should work. <br/>
<img src="https://github.com/Rastallworth1/Active-Directory-Creating-Users/blob/main/Slide%209.png"/>
<br />
<br />
As you can see in the above slide, the account (Reggie) has been enabled and you now have the option to disable it. <br/>



  
  
  
  
  


<br />
This was a simple Active Directory Home Lab / Tutorial thats demonstrates the proper steps to create a User Account.<br/>





