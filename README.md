<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

- General knowledge of user managment in osTicket
- Learn how to add users and modify permissions

<h2>Configuration Steps</h2>


<p>
Before starting, if you did not do the previous tutorial of "Prerequisites and Installation", make sure to do so to properly follow laong, we will be immediatly continuing where we left off there.
</p>
<br />

<p>
We are going to simply start with loging in, if you forgot how to do so, make sure you are in your VM, go to http://localhost/osticket/scp/login.php , and login with the credentials you used before.
</p>
<br />

<p>
![image](https://github.com/Nathantopo01/post-install-config/assets/140284822/9498e2b8-0718-445b-baa7-f5edf3a118e4)

</p>
<p>
For this, we are going to want to stay in the Admin Panel, you can easily tell if you are in the Admin Panel by seeing if on the top right it says Agent Panel for your link to go to.
</p>
![image](https://github.com/Nathantopo01/post-install-config/assets/140284822/4b34a260-85cc-4601-a840-05ec39dfb451)

<br />

<p>
![image](https://github.com/Nathantopo01/post-install-config/assets/140284822/231f934e-12de-4bee-adf7-5b1f0170ae93)

</p>
<p>
While in the Admin Panel, make your way to the Agents tab and go to Roles, on this page we will be able to add, remove, and modify roles within osTicket to suit the needs of any personell of any security level and managment they may need.
</p>
<br />

<p>
![image](https://github.com/Nathantopo01/post-install-config/assets/140284822/1d7ec295-a80d-4ea0-b23a-cd49d0185f90)

</p>
<p>
Going to Add New Role, we will see that there are not many things we can do, but will have a large impact, every Role you make will need a name associated with it and has the option to add notes below it, I would suggest adding notes as needed for yourself if you want to have some fun with the names.
</p>
<br />

<p>
  ![image](https://github.com/Nathantopo01/post-install-config/assets/140284822/5300481f-e676-49bd-9e19-5b88e2b7bd24)

</p>
<p>
Here is where you modify permissions for any role that you may make, a checkmark means that they have the ability to do what it says next to it, if you ever need to go and modify any of these you can simply go back to the Roles tab and select the name that you made the role and can modify it from there.
</p>
<br />

<p>
![image](https://github.com/Nathantopo01/post-install-config/assets/140284822/7233d7e6-0b98-483c-a207-81247d76623f)

</p>
<p>
The next tab that we will be going into is the departments tab, this allows us to actually organize our agents into wherever they need to go, be that digital maintnence, hardware side and what not. Separtments can be assigned tickets to them themselves and than a leader in the department can assign tickets to individuals from there, make sure to assign agents to the correct department so they dont get confused because they got told to write a new program from the ground up when they are there to keep the hardware running.
</p><br />

<p>
![image](https://github.com/Nathantopo01/post-install-config/assets/140284822/b0857b92-aba1-440e-928e-37170f365412)

</p>
<p>
With all that talk about Agents, lets learn how to make them, in the Agents of the Agents tab, we have the ability to see the list of all Agents, however it is just us right now, and we can add some new ones. Going into making a new agent, We can assign what department they are going to go into thier Role and also personal permissions. One thing to note is that you can make it so people can only work on assigned tickets so that a department does not get confused when multiple people try to do one ticket, however that is here or there, feel free to mess around here a bit and familiarize yourself with it.
</p>
<br />

<p>
![image](https://github.com/Nathantopo01/post-install-config/assets/140284822/d84ea19f-85ba-4aec-b1c8-6f748f63305e)

</p>
<p>
We are finally going ot be exiting the Agents tab group and go into the Manage tab. There is alot to do here but for our interests right now, we are going to go into SLA.
</p>
<br />

<p>
![image](https://github.com/Nathantopo01/post-install-config/assets/140284822/3a905081-044f-4ace-852f-539bf85ef252)

</p>
<p>
Here, we can set some levels you can say as to how severe certain tickets are, eith that be a level three Code Red the entire server is down, or a level one Code Green, the coffe machine is down (however I can see how that can be a Code Red). Alot of things here have question marks beside them, if you are never quite sure what something does simply click on the question mark and it will give you a short explanation about it. 
  ![image](https://github.com/Nathantopo01/post-install-config/assets/140284822/68158754-f52f-4c79-bfbf-f39bef5f050a)

</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
And that is all that I am going to be covering here about this, if you want to mess around with things a bit more go for it, if not make sure to clean up your Azure portal so it does not rack up a huge bill, have a beautiful day and cheers!
</p>
<br />

