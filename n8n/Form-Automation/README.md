# Form Automation

## Description
This automation is created to understand the working of n8n nodes and their internal settings and configurations.

The workflow demonstrates how form data can be captured, processed, stored in Google Sheets, and shared instantly via email.

---

## Workflow Steps

1. Create and submit an n8n form  
2. Connect Google Sheets with n8n using OAuth  
3. Execute the workflow and store submitted values in Google Sheets  
   - (Append new row in the sheet)  
4. Send an email instantly with the Google Sheet details  

---

## Tools & Services Used
- n8n
- n8n Form Trigger
- Google Sheets API
- Google Drive API
- Email (SMTP / Gmail OAuth)

---

## Use Case
- Learning n8n workflow design  
- Understanding node configuration and data flow  
- Automating form submissions  
- Storing structured data in Google Sheets  
- Instant email notifications  

---

## How to Use

1. Import the workflow JSON into n8n  
2. Configure Google Sheets OAuth credentials  
3. Configure Email credentials  
4. Update the Spreadsheet ID and Sheet name  
5. Activate the workflow  
6. Submit the form to trigger automation  

---

## Notes
- Google OAuth credentials are not included in this repository  
- Users must configure their own credentials after import  
- Sticky notes inside the workflow are used only for learning and reference  
- No sensitive information is stored in this repository  

---

## Output
- Form data appended as a new row in Google Sheets  
- Email sent instantly with submitted form details  

---

## Author
Created as part of learning AI Automation using n8n.
