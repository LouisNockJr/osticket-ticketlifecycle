<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket: Ticket Lifecycle: Intake Through Resolution</h1>
This tutorial outlines the lifecycle of a ticket from intake to resolution within the open-source help desk ticketing system osTicket.<br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (22H2)

<h2>Ticket Lifecycle Stages</h2>

- Intake
- Assignment and Communication
- Working the Issue
- Resolution

<h2>Handling a Critical Ticket: Online/Mobile Banking Outage</h2>
<p>This guide walks you through the process of creating and managing a high-priority ticket for a full online/mobile banking outage.<br />
</p>

<p>
<img src="https://i.imgur.com/rblkygA.png" height="80%" width="80%" alt="Ticket Creation"/>
</p>
<p>

  ## Step 1: Create a New Ticket (End-User)

As an end-user, create a new support ticket describing the issue:
  - **Help Topic:** Report a Problem / Business Critical Outage
  - **Subject:** Online/Mobile Banking System is Down  
  - **Description:** I cannot access online or mobile banking services. The system appears to be completely offline.

</p>
<br />

<p>
<img src="https://i.imgur.com/3ToEDCP.png" height="80%" width="80%" alt="Viewing Ticket Details"/>
</p>
<p>

  ## Step 2: View Ticket Details (Help Desk Agent: `john`)

Log in as the Help Desk Agent `john`.  
Locate the new ticket and review the following fields:

- **Priority**
- **Department**
- **SLA (Service Level Agreement)**
- **Assigned To**

</p>
<br />

<p>
<img src="https://i.imgur.com/Np0xlql.png" height="80%" width="80%" alt="Updating Ticket Properties"/>
</p>
<p>

  ## Step 3: Update Ticket Properties

Set the appropriate ticket properties based on the severity of the issue:

- **Priority:** Sev-A (1 hour, 24/7 response)
  - **Optional Reason for Update:** Wide impact, customer unable to do online banking 
- Add Context (**Optional Reason for Update**) to **Help Topic:** No customers able to do online banking
- **Department:** Online Banking Department
  - **Optional Reason for Update:** Customers not able to access online banking portal, assigning to Online Banking team.

</p>
<br />

<p>
<img src="https://i.imgur.com/NGyHiqA.png" height="80%" width="80%" alt="Reviewing Ticket Access"/>
</p>
<p>

  ## Step 4: Re-Verify Access as `john`

After updating, attempt to review the ticket again while still logged in as `john`.  

Can `john` still **view** or **edit** the ticket after changes were applied?

</p>
<br />

<p>
<img src="https://i.imgur.com/w80cSDQ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>

  ## Step 5: Resolve Ticket as `jane`

Now log in as the agent `jane`.  

Take ownership of the ticket:
  - Change **Assigned To** from `Online Banking` to `Jane Doe`
  - **Optional reason for the assignment:** I'll be taking this ticket

Perform the required troubleshooting or communication steps, and **work the ticket to completion**.

- Update the ticket with resolution details:
  - **It was determined the root cause was the recent update. We rolled it back, notified the vendor, and are waiting for a proper fix. Online banking should now be up and running.**
- Mark the ticket as **Resolved**
  
</p>
<br />

<p>
<h2> 🏁 Creating and Managing Support Tickets </h2>

As a Help Desk agent, you’ll receive support requests through many different channels — phone calls, chat messages, emails, web forms, or even in-person conversations (like someone catching you in the hallway or stopping by your desk).

While it’s perfectly okay to help someone right away when you can, **it’s important to always create a ticket for every issue you handle** — no matter how small it may seem.

## Why?

- **Tracking:** Tickets allow us to keep a record of what work is being done.  
- **Metrics:** They help us measure volume, response times, and workload.  
- **Accountability:** They ensure we’re not missing recurring issues or trends.

Even if you solve a problem on the spot, take a moment afterward to document it by creating a ticket. It’s a key part of providing consistent, reliable support.
</p>
