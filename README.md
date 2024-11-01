<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Ticket Lifecycle: Intake Through Resolution</h1>
This tutorial outlines the lifecycle of a ticket from intake to resolution within the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How to create, work, and resolves tickets within osTicket](https://www.youtube.com)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Ticket Lifecycle Stages</h2>

- Intake
- Assignment and Communication
- Working the Issue
- Resolution

<h2>Lifecycle Stages</h2>

<h2>Step 1.</h2> 

**User Sign In**
<p>
Let's begin with signing in as one of the users that was created in the previous configuration of osTicket. In this example the user will go to http://localhost/osTicket/ and click on "Sign in" in the upper right corner. Now enter in the Username and Password that was assigned to them and click "Sign In".
<p>
<p>
<img src="https://i.imgur.com/cCrb2nP.png" height="60%" width="60%" alt="Disk Sanitization Steps"/>
<img src="https://imgur.com/0xAnA8Q.png" height="60%" width="60%" alt="Disk Sanitization Steps"/>
</p>
<p>
</p>
<br />

<h2>Step 2.</h2> 

**Create New Ticket**
<p>
After signing in as a User, go to the "Open New Ticket" tab at the top of the screen. Now choose a "Help Topic" that best fits the issue that is occuring -> Next type in an "Issue Summary" of the problem. -> below that enter in a more detailed description so that the Agents have a good idea of what's going on and how to resolve it. -> click "Create Ticket" to submit it. Now you can see the newly created ticket, with it's own ticket number next to the "Issue Summary", the date and time created, the User who issued it, and the description of the problem.
<p>
<p>
<img src="https://i.imgur.com/bDkiuYs.png" height="60%" width="60%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/fAAkSJZ.png" height="60%" width="60%" alt="Disk Sanitization Steps"/>
</p>
<p>
</p>
<br />

<h2>Step 3.</h2> 

**Submit Additional Tickets**
<p>
Now for practic let's submit additional tickets with varying topics and issues for the Agents to resolve.
<p>
<p>
<img src="https://i.imgur.com/mIYjWZy.png" height="60%" width="60%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/AAwf8Dr.png" height="60%" width="60%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/YGQYiia.png" height="60%" width="60%" alt="Disk Sanitization Steps"/>
</p>
<p>
</p>
<br />

<h2>Step 4.</h2> 

**Agent Sign In**
<p>
Now that several tickets have been submitted, it's time for the Agents to respond to them. Let's begin by signing in as one of the Agents (in this case Jane Doe) we created in the previous tutorial. 
<p>
<p>
<img src="https://i.imgur.com/XogvqBw.jpg" height="60%" width="60%" alt="Disk Sanitization Steps"/>
</p>
<p>
</p>
<br />

<h2>Step 5.</h2> 

**Answering Tickets**
<p>
The Agent can now see all the open tickets they have access to and notices that there is a "Emergency" priority level ticket that is effecting the shopping cart. They click on the ticket to open it and examine it further. The Agent can now see that this ticket is showing that customers are unable to view their shopping cart to complete their purchase. They check above and take note of the following: "Priority" is set to "Emergency", it is "Assigned to" no Agent yet, the "Help Topic" is set to "Business Critical Outage", the "SLA Plan" is set to "Sev-A" (the higest SLA that was setup in the previous tutorial, that needs to be answered within 1hr on a 24/7 schedule) and that the Department is set to "Support". After reviewing this, the Agent considers the severity and knows that the System Administrators are responsible for all "Business Critical Outage" tickets and reassigns it to their Department. They do this by clicking on the "Support" Department highlighted in blue and selects "System Administrators", and leaves a note explaining why they are transferring it. They then contact the Sytem Admin (in this example Joe) to notify them about the situation.
<p>
<p>
<img src="https://i.imgur.com/CA9NjRa.png" height="60%" width="60%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/TyVoyUJ.png" height="60%" width="60%" alt="Disk Sanitization Steps"/>
</p>
<p>
</p>
<br />

<h2>Step 6.</h2> 

**Answering Tickets (continued)**
<p>
The Admin opens the ticket on their computer and reads about the problem. They see that Agent Jane Doe originally reviewed this ticket and rightly reassigned it to the appropriate Department. Next the Admin assigns the ticket to themselves (since it is their responsibility in this case) by clicking on the "Unassigned" grayed out and selecting their name.They now begin to write a response explaining the steps they are taking to resolve the issue, and post the reply. After some time, in this theoretical example the Admin resolves the issue by working with the System Engineer. They open the ticket once more and post a reply stating the error has been fixed and make sure to change the "Ticket Status" to "Resolved" before posting the reply. This will now close this ticket out. You will notice that every action is documented on the ticket, to easily reference all the steps taken to resolve it.
<p>
<p>
<img src="https://i.imgur.com/zQHyVPa.png" height="60%" width="60%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/UgO5syE.png" height="60%" width="60%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/P4PknKo.png" height="60%" width="60%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/J82e6nj.png" height="60%" width="60%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/cXxxY6i.png" height="60%" width="60%" alt="Disk Sanitization Steps"/> 
<img src="https://i.imgur.com/5f2X3my.png" height="60%" width="60%" alt="Disk Sanitization Steps"/> 
<img src="https://i.imgur.com/9Iu2gPR.png" height="60%" width="60%" alt="Disk Sanitization Steps"/> 
</p>
<p>
</p>
<br />

<h2>Step 7.</h2> 

**Closed Tickets**
<p>
Here are a few more basic examples of the tickets we created getting replied to and resolved. You can view all the closed tickets by going to the "Closed" tab under "Tickets".
<p>
<p>
<img src="https://i.imgur.com/yof2jHK.png" height="60%" width="60%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/otmEvqU.png" height="60%" width="60%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/I5ETCul.png" height="60%" width="60%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/CLSL7M2.png" height="60%" width="60%" alt="Disk Sanitization Steps"/>
</p>
<p>
</p>
<br />
<h2> <p align="center"> This Concludes the osTicket Lifecycle Tutorial.</h2>
