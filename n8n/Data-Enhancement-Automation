# Customer Data Enrichment Automation

## Description
This workflow automates the process of enriching potential customer data using external prediction APIs and storing the enriched data in Google Sheets.

It predicts customer gender, age, and nationality based on the customer name, updates the Google Sheet accordingly, and sends an email notification when a new customer signs up.

---

## Workflow Steps

1. Create and maintain a Google Sheet for potential customers  
2. Fetch predicted **gender** using an HTTP Request based on the customer name  
3. Fetch predicted **age** using an HTTP Request based on the customer name  
4. Fetch predicted **nationality** using an HTTP Request based on the customer name  
5. Append or update customer details in Google Sheets  
6. Send an email notification confirming that a new customer has been signed up  

---

## Tools & Services Used
- n8n
- Google Sheets API
- Google Drive API
- HTTP Request node (external prediction APIs)
- Email (SMTP / Gmail OAuth)

---

## Use Case
- Lead data enrichment  
- Customer onboarding automation  
- Marketing and CRM preparation  
- Reducing manual data entry  
- Learning API integration with n8n  

---

## How to Use

1. Import the workflow JSON into n8n  
2. Configure Google Sheets OAuth credentials  
3. Configure Email credentials  
4. Update the Spreadsheet ID and Sheet name  
5. Ensure required APIs are accessible  
6. Execute or activate the workflow  

---

## Output
- Enriched customer data stored in Google Sheets  
- Existing customer rows updated if already present  
- Email notification sent for each new customer signup  

---

## Notes
- OAuth credentials are not included in this repository  
- Users must configure their own credentials after import  
- External APIs used for prediction may have rate limits  
- Workflow created for learning and automation practice  

---

## Author
Created as part of learning AI Automation using n8n.
