# n8n-email-agent-demo
AI Agent workflow in N8N that sends automated emails using OpenAI + Gmail

# Email Automation AI Agent (N8N)

## 📌 Overview
This project demonstrates an **AI Agent workflow built in N8N** that can:
- Read chat instructions (who to send email + what to write)
- Generate short, clear email content using **OpenAI Chat Model**
- Maintain context with **Simple Memory**
- Send the email automatically via **Gmail integration**

---

## 🔄 Workflow Flow
1. **Trigger** → Workflow starts when a chat message is received.  
2. **AI Agent** → Interprets the chat message.  
   - Extracts **recipient email ID**  
   - Extracts **topic/subject**  
3. **OpenAI Chat Model** → Generates the email body in short points.  
4. **Gmail Node** → Sends the email automatically to the given address.  
5. **Final Response** → AI Agent confirms back in chat: **Done.**

👉 Flow: **Chat Input → AI Agent → OpenAI → Gmail → AI Agent → Response**

---

## 🧪 Demo
Example query:  


**Output:**  
- Gmail sends the email with the requested content.  
- AI Agent confirms: **Done.**

---

## ⚙️ How to Run
1. Download `emailWorkflow.json` from this repo.  
2. In N8N, go to **Import from file** and upload the JSON.  
3. Connect your Gmail account in N8N.  
4. Run the workflow and send a chat message to which mail id we sendinf msg for what purpose.  
5. The agent will automatically generate and send the email, then confirm the action.

---

## 📂 Files
- `emailWorkflow.json` → Workflow export file (import into N8N).  
- Screenshot → Proof of working agent.
- email -> Email received at receiver email proof of screenshot.  

---

