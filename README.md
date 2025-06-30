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

<h3>Ticket 1</h3>
<p><b>This first example will also function as a partial tutorial to show the dialog menus and the proper responses contained within each interaction.</b></p>
<p>
<img src="https://imgur.com/PjUibby.png" height="80%" width="80%" alt="Open ticket">
</p>
<p>
To simulate a user submitting a ticket, navigate to localhost/osTicket/, and click "Open a New Ticket".
</p>
<br />

<p>
<img src="https://imgur.com/KCnI5z4.png" height="80%" width="80%" alt="Ticket information">
</p>
<p>
Manager karen has had reports of issues with online banking and is opening a ticket. (Not all information a user provides may be correct, e.g., Help topic: Report a Problem, the more appropriate would be: Report a Problem / Business Critical Outage)
</p>
<br />

<p>
<img src="https://imgur.com/R4E8fHE.png" height="80%" width="80%" alt="Ticket unedited">
</p>
<p>
This is how the ticket would first appear to a help desk agent prior to assigning it to the correct team (if applicable).

<b>Let's update the ticket information so the appropriate team handles the issue.</b>
</p>
<br />

<p>
<img src="https://imgur.com/3I4ZFqd.png" height="80%" width="80%" alt="SLA update">
</p>
<p>
First, update the SLA to the appropriate severity level. (Sev-A)
</p>
<br />

<p>
<img src="https://imgur.com/9AdrAgT.png" height="80%" width="80%" alt="Help Topic update">
</p>
<p>
Next, the help topic so the proper support team knows the scope of work it may entail. 
</p>
<br />

<p>
<img src="https://imgur.com/JDG06lJ.png" height="80%" width="80%" alt="Team update">
</p>
<p>
Finally, assign the ticket to the correct team so they can start addressing the issue.

<b>Assigning the team last will make sure you can make all the proper adjustments to the ticket before potentially losing access (only if you do not have access to tickets from the team your assigning it to).</b>
</p>
<br />

<p>
<img src="https://imgur.com/P51eTDg.png" height="80%" width="80%" alt="Updated Ticket">
</p>
<p>
This is an updated view of the ticket, all the information has been updated and also the timeline of all edits made to the ticket.
</p>
<br />

<p>
<img src="https://imgur.com/SCCHsqY.png" height="80%" width="80%" alt="Self assignment">
</p>
<p>
Once a ticket has been reassigned to the correct support team, the team takes over to work the ticket. An individual on the team will usually get it assigned to them or take the assignment themselves so it can be tracked under their name.
</p>
<br />

<p>
<img src="https://imgur.com/3ohD2gM.png" height="80%" width="80%" alt="Working the ticket">
</p>
<p>
As the suppoort member intracts with the user and resolves the ticket, they will send updates in accordance with the SLA type. These updates and interactions will be saved in in the timeline history of the ticket.
</p>
<br />

<p>
<img src="https://imgur.com/POqDVuc.png" height="80%" width="80%" alt="Ticket resolution">
</p>
<p>
Upon completion of the ticket it will need to be closed or resolved. Resolved is always the preferable outcome, on occasion, closing may be preferable. 

When there's been no response from the user after multiple attempts to contact them, the issue is deemed a duplicate or spurious, or when the user indicates the issue is resolved but doesn't explicitly confirm resolution by closing the ticket. Closing would be prefferable. 
</p>
<br />

<h3>Ticket 2</h3>
<p>
<img src="https://imgur.com/buk1dqJ.png" height="80%" width="80%" alt="Ticket 2 open">
</p>
<p>
This ticket has already been created from the accounting team. Since there is only one other team, "Online Banking", this will be handled by the support team. Your support user can open it up and properly assign and work the ticket.
</p>
<br />

<p>
<img src="https://imgur.com/gVejj9X.png" height="80%" width="80%" alt="Ticket 2 assign">
</p>
<p>
Notice how all applicable fields have beeen updated. Support agent Jacob did his due diligence prior to SLA assignment this time (not typical but can save time in some scenarios). 

After contacting the user experiencing the problem, he was able to decern an apropriate SLA for the ticket. Gathering this information allowed Jacob to hone his scope of work down from an entire team experiencing the issue to finding out it was only two devices. 

Jacob also kept open communication with the ticket, properly setting a time for follow up to address the issue further if necessary. This would allow for his work load to not be held up by one single ticket.
</p>
<br />

<p>
<img src="https://imgur.com/we0d1Dn.png" height="80%" width="80%" alt="Ticket Resolution">
</p>
<p>
Due to Support agent Jacob solving the issue he was able to resolve the ticket and close out.
</p>
<br />
 <h3>Ticket 3 - Closed</h3>
<p>
<img src="https://imgur.com/7XKVTpl.png" height="80%" width="80%" alt="Navigate to closed tickets">
</p>
<p>
Sometimes a problem could recieve multiple tickets, or a common issue may arise often. In these cases being able to go back and assess how the issue was resolved previously can assist in working new tickets. By navigating to a closed ticket, we can view useful information about it.
</p>
<br />

<p>
<img src="https://imgur.com/OX0wYBT.png" height="80%" width="80%" alt="Closed ticket">
</p>
<p>
As shown, this is a resolved ticket that was closed out by Support agent "Jacob West". The same as if you were working the ticket you can see all the information about the timeline, SLA level, Help Topic, and the agents that interacted with the ticket.
</p>
<br />

<p>
<img src="https://imgur.com/cgi5t7X.png" height="80%" width="80%" alt="Link tickets">
</p>
<p>
If a reported issue is persistent after an initial ticket was closed or resolved, it may be useful to merge or link the previous ticket to a new one. 

Merging will make the tickets history combine with the new one, this can be useful but can cause confusion if the dates of the tickets span a large amount of time. 

To avoid confusion and clarify that new or different work has been done on an old issue. Linking tickets will allow keeping seperate "histories" of the tickets but will associate them together for easy access and referencing in the future.
</p>
