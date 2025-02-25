<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Ticket Lifecycle: Intake Through Resolution</h1>
This tutorial outlines the lifecycle of a ticket from intake to resolution within the open-source help desk ticketing system osTicket.<br />

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

<p>
<img width="1422" alt="Screenshot 2025-01-24 at 2 18 47 PM" src="https://github.com/user-attachments/assets/478e5d43-eca5-474a-b44c-720401da906c" />
</p>
<p>
I first created a ticket as a user that claimed the entire online banking department was down. I then logged into oSTicket with one of the agent profiles I created "Jessica". Since the user did not correctly classify the problem as "Business Critical", I changed the default SLA to Sev-A.
</p>
<br />

<p>
<img width="465" alt="Screenshot 2025-01-24 at 3 08 28 PM" src="https://github.com/user-attachments/assets/a9dd51c0-3dd6-4b40-80ba-3af7ffed0565" />
</p>
<p>
Then as Jessica, I assigned the ticket to the online banking team. I logged back in as Brad, who is a member of this team and began to work the issue. I responded to the user and said that this may be from a recent update. I said I would roll back this update and determine if that was the root cause of the issue. 
</p>
<br />

<p>
<img src="https://i.imgur.com/j4U0CGP.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
After confirming that the updates were the root cause of the issue, I rolled back the updates and returned online banking back to functionality. I made this known to the user and let them know I would be reaching out to the vendor. I then marked the ticket as resolved. 
</p>
<br />
