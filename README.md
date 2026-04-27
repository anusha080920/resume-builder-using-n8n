# resume-builder-using-n8n
Overview:
This project generates a professional resume using n8n workflows. It takes user data and converts it into a styled HTML resume

How it Works:
Webhook triggers the workflow
User data is processed
Code node generates HTML
Resume is displayed in browser

Workflow:

Webhook → Edit Fields → Code → HTML → Respond
Output:

A styled resume page displayed in the browser.

Tech Used:      n8n
              JavaScript
              HTML & CSS
              
Challenges:API quota issues
           JSON errors
           Webhook method mismatch
Solutions:  Removed API dependency
            Fixed JSON structure
            Used GET method for browse
