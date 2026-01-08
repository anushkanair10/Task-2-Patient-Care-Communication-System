# Task-2-Patient-Care-Communication-System

# Patient Care & Communication System

This system reduces a doctor’s non-clinical workload by moving WhatsApp chaos into a structured Google Sheets dashboard. It limits doctor review time to **≤10 minutes per session**.

## Project Files

### 1. [Care_Control Dashboard](https://docs.google.com/spreadsheets/d/1juHPYBVYqAhiNLriFDq8-WkAQy-8iV-bAVNBQC4aEMo/edit?usp=sharing)
* **Role**: The main "Command Center" where daily patient interactions are tracked.
* **Logic**: Automatically drafts messages and flags "High Priority" items for the doctor.

### 2.(i) [Patient_Questions (Response Sheet)](https://docs.google.com/spreadsheets/d/1WvGxB2Ke04ftFVF4EmfbKgLw_R-sjpF_FgEzmFWUmok/edit?usp=sharing)
### (ii) [Form](https://docs.google.com/forms/d/e/1FAIpQLSfSFwSkUDLtzxoPIfyjfKygnlARuDj6s4dPsRlVOmJo2pOCHA/viewform?usp=dialog)
* **The Form**: A structured intake portal for patients to submit queries (Name, Phone, Question, Urgency) .
* **The Sheet**: The live destination where form responses are automatically stored for batch review .

### 3. [Automation Script](in uploaded pdf)
* **Role**: Google Apps Script that reads pending rows and sends messages via WhatsApp API .
* **Feature**: Automatically updates the status to "Sent" once the message is dispatched.
