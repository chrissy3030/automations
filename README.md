This repository contains images of my n8n workflows and automation projects. 
These are made from scratch and tested end to end, ready to use, unless stated otherwise. 

Content:

  - Workflow 1: Daily Status + Telegram Alert (Basic Workplace)

  - Workflow 2: Email booking + Database Auto update (Basic Workplace)

  - Workflow 3: Time sensitive tracking + Delay alert (Urgent Tasks)
	


## Workflow 1: Daily Status + Telegram Alert

**Description:**  
Agent automatically reads data from Google Sheets and sends a clean daily status report via Telegram.

### Workflow Diagram (Excalidraw)
![Excalidraw Diagram](images/status-bot-1-excalidraw.png)

### n8n Workflow Screenshot
![n8n Workflow](images/status-bot-1-n8n.png)


## Workflow 2: Email booking + Database Auto update

**Description:**  
Agent extracts information from specific new emails and fills up the related database automatically while also sending a telegram alert.

### Workflow Diagram (Excalidraw)
![Excalidraw Diagram](images/Email-booking+Database-Auto-update-excalidraw.png)

### n8n Workflow Screenshot
![n8n Workflow](images/Email-booking+Database-Auto-update-n8n.png)

### screenshots of the email - updated database(google sheets) - telegram alert 
![Trigger Email](images/Email-booking+Database-Auto-update-trigger-email.png)
![Updated Database](images/Email-booking+Database-Auto-update-database.png)
![Telegram Alert](images/Email-booking+Database-Auto-update-telegram-alert.png)


## Workflow 3: Time sensitive tracking + Delay alert 

**Description:**  
Agent uses filtered information from database to for a sceduled alert for delays. Informs users of time sensitive taks on a fixed routine. 

### Workflow Diagram (Excalidraw)
![Excalidraw Diagram](images/Time-sensitive-tracking+Delay-alert-excalidraw.png)

### n8n Workflow Screenshot
![n8n Workflow](images/Time-sensitive-tracking+Delay-alert-n8n.png)

### Database(google sheets) - telegram alert 
![Database](images/Time-sensitive-tracking+Delay-alert-database.png)
![Telegram Alert](images/Time-sensitive-tracking+Delay-alert-telegram.png)

---
