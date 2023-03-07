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
Similar to creating User accounts, only the blocks with the red Asterisks is required.  You can add additional information in the Description and Notes if desired. Once you are done, click OK to have the group created.<br/>



<br />
Now we want to add the C Plus Developers group to the Developers group that already exists. We can do this by scrolling down to the new entry and then right clicking on the entry in the list and selecting the Add to another group entry. <br/>
<img src="https://github.com/Rastallworth1/Active-Directory-Creating-and-Managing-groups/blob/main/slide%203.jpg"/>
<br />


<br />
This will open a small window where we need to enter the name of the group. In this case, the group is called Developers. You can use the Check Names button to verify that you have entered the name correctly. If you have, it will underline the text. If the name is incorrect, it will show a window saying "Name Not Found. Clicking the OK button will add the C Plus Developers group to the Developers group. <br/>
<img src="https://github.com/Rastallworth1/Active-Directory-Creating-and-Managing-groups/blob/main/Slide%203%20bottom.jpg"/>
<br />



<br />
To verify, we will double click the Python Developers entry in the list, which will open up an editing window for the group. Scroll down until you find the Members section of this window, or you can click on the Members link on the left. This section will show that C Plus Developers are a part of the larger Developers group. <br/>
<img src="https://github.com/Rastallworth1/Active-Directory-Creating-and-Managing-groups/blob/main/slide%204%20top.jpg"/>
<br />
<br/>
<img src="https://github.com/Rastallworth1/Active-Directory-Creating-and-Managing-groups/blob/main/slide%204%20bottom.jpg"/>
<br />
 

  


<br />
This was a simple Active Directory Home Lab / Tutorial thats demonstrates the proper steps to create a group and add it to a larger group.<br/>





