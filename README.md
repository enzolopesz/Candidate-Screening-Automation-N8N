# Project 1 — Candidate Screening Automation (n8n)

This project is an automation workflow built in **n8n** to handle the first stage of candidate applications, reducing manual effort and ensuring a faster and more consistent screening process.

---

## Candidate

**Enzo Lopes**

- Workflow designed to improve recruitment efficiency  
- Currently applying for opportunities  

---

## Naming Conventions

- **Trigger** → The event that starts the automation  
- **Node** → Each individual step inside the workflow  

---

## Workflow Functions

### 1. Initial Candidate Validation

The first screening checks basic requirements such as:

- Expected salary  
- General compatibility with the position  

If the candidate does not meet the criteria, the workflow automatically sends a rejection message.

---

### 2. Candidate Data Intake

If the candidate passes the initial validation:

- Their information is collected and processed  
- The application moves forward to the next stage

---

### 3. Manager Notification

When a candidate is approved:

- An email is sent to the hiring manager  
- The manager is notified that a new candidate is available for review

---

### 4. Interview Scheduling Filter

After manager review:

- The candidate may receive an interview scheduling link  
- If not approved, the workflow ensures proper communication and closure

---

## Goal

To create a simple, predictable, and maintainable recruitment automation that improves speed and reduces repetitive manual tasks during candidate screening.
