# 🌟 Daily Motivation Emailer (n8n Workflow)

This project automatically sends motivational quotes to your email every morning using **n8n**, an open-source workflow automation tool.

---

## 🚀 Features
- Sends a new motivational quote every day at a scheduled time.
- Uses **HTTP Request Node** to fetch random quotes from a public API.
- Formats and sends the quote via **Email Node**.
- Fully automated using n8n workflow triggers.
- Customizable for any email list or message type.

---

## 🧠 How It Works

1. **Trigger Node** – Runs daily at a set time (e.g., 8 AM).
2. **HTTP Request Node** – Fetches a random quote from an API like:
3. **Function Node (optional)** – Formats the quote text and author neatly.
4. **Email Node** – Sends the quote to your email address automatically.

---

## ⚙️ Setup Instructions

### Prerequisites
- Installed n8n (via npm or Docker)
- A valid email SMTP service (e.g., Gmail, Outlook, etc.)
- Internet connection to fetch quotes from API

### Steps
1. Open n8n in your browser (default: https://manoj9990.app.n8n.cloud/)
2. Create a new workflow and add:
- **Trigger → HTTP Request → Email Node*
3. Configure your email credentials in the **Email Node**
4. Save and activate the workflow
5. Test the email to ensure it sends successfully

## 🌐 Deploying Online
You can deploy n8n online using:
- **n8n.cloud** (official hosted version)
- **Render / Railway.app / Vercel (Docker-based deployment)**
- **Google Cloud Run or AWS EC2**

## 💾 Version Control with GitHub

To upload this project to GitHub:

```bash
# Initialize git in your project folder
git init

# Add files
git add .

# Commit the project
git commit -m "Initial commit: Daily Motivation Emailer using n8n"

# Create new repo in GitHub (empty one) and copy the repo URL
git remote add origin https://github.com/<your-username>/n8n-daily-motivation.git

# Push your project
git push -u origin main
