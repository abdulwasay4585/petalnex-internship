---

created: 2026-07-22 15:50  
updated: 2026-07-22 15:50  
course_code:  
semester:  
credits:  
instructor:  
department:  
status: Ongoing  
tags:

- course  
    aliases: []
    

---

# 📘 Day 1

---

# 🎯 Learning Objectives

By the end of this course I should be able to:
![Learning Objectives Screenshot](Screenshot%20From%202026-07-22%2016-03-23.png)
    
---

# 📂 Assignments

![Assignments Screenshot](Screenshot%20From%202026-07-22%2016-12-01.png)

[Automation Opportunities PDF](Automation-Opportunities..pdf)

## 1. Accounts Payable Invoice Processing

- **Process Name:** Accounts Payable Invoice Processing and Matching
    
- **Current Manual Process:** Accounts payable staff receive vendor invoices via email attachments or postal mail. They manually type invoice details into accounting software, visually cross-reference[...]
    
- **Problem:** Manual data entry causes typos and duplicate payments. Approval requests sit unread in email inboxes, leading to missed early payment discounts, late penalties, and vendor friction.
    
- **Trigger:** Receipt of a vendor invoice via email, portal, or physical mail.
    
- **Input:** Vendor invoice (PDF or paper image), Purchase Order (PO) record, Goods Received Note (GRN).
    
- **Processing Required:**
    
    - Extract text, invoice numbers, and line items using Optical Character Recognition (OCR).
        
    - Perform a three way match comparing invoice line items against PO quantities and GRN pricing.
        
    - Route unmatched invoices or price discrepancies to the designated buyer for exception review.
        
    - Automatically route matched invoices to the department head for one click approval.
        
    - Create the payment voucher directly in the ERP system.
        
- **Expected Output:** Verified payment voucher posted in the accounting ledger, scheduled electronic payment, and audit trail record.
    
- **Benefits of Automation:**
    
    - Cuts processing time from weeks to minutes.
        
    - Eliminates duplicate payments and data entry errors.
        
    - Captures early payment discounts and avoids late fees.
        

## 2. Employee Onboarding and IT Provisioning

- **Process Name:** Employee Onboarding and Account Provisioning
    
- **Current Manual Process:** HR collects new hire documents via email, enters personal information into the HR Information System (HRIS), and emails IT a checklist for needed equipment and software. [...]
    
- **Problem:** Manual setups leave new employees waiting days for software access, reducing first week productivity. Human oversight can also leave security gaps by assigning incorrect permission leve[...]
    
- **Trigger:** Candidate accepts an offer letter in the applicant tracking system.
    
- **Input:** Signed offer letter, new hire profile details, job title, department, manager name.
    
- **Processing Required:**
    
    - Sync new hire records automatically from the applicant tracking system into the HRIS.
        
    - Create corporate email addresses and central identity credentials.
        
    - Provision role-based access across required platforms (such as communication tools, project managers, and CRM systems).
        
    - Dispatch a automated welcome email with login instructions and first day schedule.
        
    - Send hardware fulfillment tickets to logistics.
        
- **Expected Output:** Active user accounts, provisioned software licenses, welcome onboarding packet sent, and hardware tracking ticket.
    
- **Benefits of Automation:**
    
    - Guarantees full system access on the employee's first day.
        
    - Reduces HR and IT administrative workload by up to 80 percent.
        
    - Standardizes role-based access control and security compliance.
        

## 3. Employee Expense Report Auditing

- **Process Name:** Employee Expense Audit and Reimbursement
    
- **Current Manual Process:** Employees fill out spreadsheet templates, attach receipt photos, and email them to managers. Managers review receipts item by item, approve via email, and forward to fina[...]
    
- **Problem:** Reviewing receipts line by line is slow and prone to oversight. Employees experience delayed reimbursements, and policy violations go undetected due to manual review fatigue.
    
- **Trigger:** Employee submits a new expense claim through the expense portal or mobile app.
    
- **Input:** Receipt images, expense line items (amount, date, merchant, expense category), corporate travel policy rules.
    
- **Processing Required:**
    
    - Extract receipt metadata (merchant, date, total, tax) using receipt parsing technology.
        
    - Cross-check receipt information against submitted claim data to flag mismatched totals.
        
    - Evaluate expense lines against corporate policy rules (such as daily meal allowances or non-reimbursable categories).
        
    - Automatically approve compliant expenses under a specified dollar threshold.
        
    - Route non-compliant claims or high value expenses to department managers with highlighted flags.
        
    - Push approved reimbursement batches directly to accounts payable or payroll.
        
- **Expected Output:** Approved reimbursement batch file, automated status updates to the employee, and audit logs.
    
- **Benefits of Automation:**
    
    - Accelerates employee reimbursement turnaround from weeks to days.
        
    - Identifies policy violations and duplicate receipt submissions instantly.
        
    - Minimizes time finance teams spend reviewing routine receipts.
        

## 4. Customer Support Ticket Triage and Routing

- **Process Name:** Customer Support Ticket Triage and Assignment
    
- **Current Manual Process:** Support managers monitor a master inbox or unassigned queue, read incoming customer messages, evaluate urgency and topic, and manually assign each ticket to an available [...]
    
- **Problem:** Ticket assignment slows down during high volume periods or off-peak hours. Misrouted tickets get passed between agents repeatedly, increasing response times and frustrating customers.
    
- **Trigger:** Customer submits a support inquiry via web form, email, or live chat.
    
- **Input:** Customer message body, customer tier or account status, historical interaction records.
    
- **Processing Required:**
    
    - Analyze message text using natural language processing to identify intent, sentiment, and urgency level.
        
    - Classify the ticket category (such as billing issue, technical bug, or account access).
        
    - Evaluate agent skills, spoken languages, account assignments, and real-time workload.
        
    - Route the ticket directly to the best-suited agent or send instant self-service solutions for routine queries.
        
    - Escalate high tier customers or urgent negative sentiment tickets to team leads immediately.
        
- **Expected Output:** Categorized, prioritized, and assigned support ticket complete with customer context for the agent.
    
- **Benefits of Automation:**
    
    - Reduces initial response times from hours to seconds.
        
    - Prevents ticket bouncing between internal teams.
        
    - Ensures even workload distribution across support teams.
        

## 5. Vendor Contract Renewal Management

- **Process Name:** Vendor Purchase Order and Contract Renewal Management
    
- **Current Manual Process:** Procurement maintains contract expiration dates in static spreadsheets. Procurement officers manually email business owners when dates approach, circulating renewal terms[...]
    
- **Problem:** Static tracking leads to missed cancellation windows, causing unintentional auto-renewals for unused services. Unstructured email approvals create security risks and leave poor audit tr[...]
    
- **Trigger:** System alert triggered 90, 60, or 30 days prior to contract expiration date, or a new purchase order request submitted by a user.
    
- **Input:** Contract metadata (expiration date, cancellation notice period, vendor contact, annual value), purchase request details.
    
- **Processing Required:**
    
    - Scan contract repository continuously for upcoming renewal deadlines.
        
    - Generate renewal notification tasks and send usage analytics to the contract owner.
        
    - Compare purchase request dollar amounts against corporate authorization tiers.
        
    - Route requests through sequential approval workflows for digital signatures.
        
    - Sync approved purchase orders into accounting systems automatically.
        
- **Expected Output:** Timely contract renewal decisions, digitally signed vendor agreements, and active purchase orders.
    
- **Benefits of Automation:**
    
    - Prevents unwanted auto-renewals and eliminates redundant software spend.
        
    - Delivers complete corporate visibility into upcoming vendor obligations.
        
    - Enforces compliance with internal financial delegation thresholds.

---

# 💻 Checklist

- [ ]All Accounts created according to the appendix B in the docuement
		![Checklist Screenshot](Screenshot%20From%202026-07-22%2016-03-23.png)
	
- [ ]

---

# 📚 Resources

| Title                                              | Status                              |
| -------------------------------------------------- | ----------------------------------- |
| n8n – Try it / Cloud sign-up                       | https://n8n.io/                     |
| n8n Academy (official free courses & certificates) | https://docs.n8n.io/courses/        |
| n8n Docs – Learning paths                          | https://docs.n8n.io/learning-paths/ |
|                                                    |                                     |

---

# 🧠 Important Concepts


---

# 💻 Code Examples

---

# ❓ Frequently Asked Questions

### Question 1
Identify 5 real manual business processes that could be automated
Answer
Recruitment, Support, Sales, Marketing, Finance

---

### Question 2

Answer

---

### Question 3

Answer

---

# 📅 Timeline

|Week|Topics|
|---|---|
|1||
|2||
|3||
|4||
|5||

(Add more weeks as needed.)

---

# 📋 Revision Checklist

-  Finished syllabus
    
-  Reviewed lecture notes
    
-  Solved assignments
    
-  Completed labs
    
-  Practiced coding
    
-  Reviewed formulas
    
-  Attempted past papers
    
-  Created flashcards
    

---

# 🔗 Related Notes

- [[ ]]
    
- [[ ]]
    
- [[ ]]
    

---

# 💭 Personal Notes

Write important observations, study strategies, or reminders.

---

# 📅 Study Log

|Date|Activity|
|---|---|
|2026-07-22|Course page created|
