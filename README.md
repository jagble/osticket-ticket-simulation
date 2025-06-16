# osticket-ticket-simulation

<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

# OsTicket-Ticket-Simulation
## 🧪 Part 3: Ticket Simulation

In this section, we will simulate real-world usage of the osTicket ticketing system by walking through four different tickets. Each ticket will:

- Be submitted by one of the two users created in the previous sections (**Jordan** or **Taylor**)
- Be routed to the appropriate **department**
- Involve the correct **agent** based on their **team**, **role**, and **department**
- Allow us to explore **permissions**, **SLAs**, and **ticket resolution flow**

We’ll be logging in as both **end users** and **agents** to simulate how tickets are created, assigned, and worked on in the field.



<h2>Video Demonstration</h2>

- ### [YouTube: How To Install osTicket with Prerequisites](https://www.youtube.com)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

- [OsTicket Download](https://drive.google.com/uc?export=download&id=1b3RBkXTLNGXbibeMuAynkfzdBC1NnqaD)
- [Pre-Installation Checklist](https://docs.google.com/document/d/1DyjX8LeVU98LjhXO2t2K2F0aHywI2N9GD57T3taO5qo/edit?tab=t.0)

<h2>Ticket Simulation Steps</h2>


### 🎫 Ticket 1: Password Reset Request

- **Submitted by:** Jordan  
- **Help Topic:** Password Reset  
- **Department:** Support  
- **Assigned Team:** Level 1 Support  
- **Assigned Agent:** Tyrese Haliburton (Tier 1 Tech)  
- **SLA:** Sev-B (4 hours)

**Flow:**

1. Log in as **Jordan**
2. Navigate to “Open a New Ticket”
3. Fill in the issue: _“I’m locked out of my computer and need to reset my password.”_
4. Submit the ticket
5. Log out as Jordan and log in as **Tyrese Haliburton**
6. View the ticket, confirm SLA and help topic
7. Add a note and respond to the user

---

### 🎫 Ticket 2: Laptop Encryption Issue

- **Submitted by:** Taylor  
- **Help Topic:** Equipment Request  
- **Department:** SysAdmins  
- **Assigned Team:** Security Ops  
- **Assigned Agent:** Anthony Edwards (Supreme Admin)  
- **SLA:** Sev-A (1 hour)

**Flow:**

1. Log in as **Taylor**
2. Submit the issue: _“My laptop says it’s not encrypted — I need help ASAP.”_
3. Log out, log in as **Moses Moody** (Intern)
4. View the ticket — observe that access is read-only
5. Log out, log in as **Anthony Edwards**
6. Assign ticket to yourself and begin working

---

### 🎫 Ticket 3: Google Ads Access Request

- **Submitted by:** Jordan  
- **Help Topic:** Other  
- **Department:** Support  
- **Assigned Team:** Level 1 Support  
- **Assigned Agent:** Tyrese Haliburton  
- **SLA:** Sev-C (8 hours)

**Flow:**

1. Log in as **Jordan**
2. Submit the issue: _“Need access to Google Ads dashboard for upcoming campaign.”_
3. Log in as **Tyrese Haliburton**
4. Assign, set SLA, respond to user

---

### 🎫 Ticket 4: VM Exposed to Public

- **Submitted by:** Taylor  
- **Help Topic:** Business Critical Outage  
- **Department:** Cloud Infrastructure  
- **Assigned Team:** Security Ops  
- **Assigned Agent:** Klay Thompson (Cloud Security Engineer)  
- **SLA:** Sev-A (1 hour)

**Flow:**

1. Log in as **Taylor**
2. Submit the issue: _“I noticed a VM with port 3389 exposed to the public.”_
3. Log out, log in as **Klay Thompson**
4. Assign and acknowledge the ticket
5. Update the ticket with steps taken or recommendations


---

## 🧠 Real-World Ticket Intake Notes

- In real helpdesk environments, tickets can originate from:
  - Phone calls
  - Chat apps (e.g., Teams, Slack)
  - Emails
  - Web forms
  - In-person “walk-ups”

- People might approach you with on-the-spot issues. While it’s fine to fix them immediately:
  > 🎯 **Always create a ticket for what you do.**  
  > Why? Because **metrics matter** — they help track your productivity and identify recurring issues.

---

## 🚀 Wrapping Up & Practice Suggestions

- There's much more to osTicket than we've covered here — explore it!
- Try enabling and testing the **email features** for notifications and replies.
- **Repeat this lab** a few times until you can confidently implement it with just a checklist.
- As you build up your technical skills, redoing this lab will boost your confidence and intuition.
- Understanding systems like osTicket builds a foundation for real-world IT roles.
 - Get comfortable managing roles, permissions, and the flow of tickets.

> 💡 Each repetition sharpens your technical instincts and prepares you for handling real environments with ease.

---

