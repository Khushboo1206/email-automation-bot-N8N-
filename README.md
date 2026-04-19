# 📧 Email Automation Bot using n8n

## 🚀 Project Overview

This project demonstrates a simple **workflow automation system** built using **n8n**. It automates data flow by connecting nodes and storing results in Google Sheets.

### 🔄 Workflow:

* Manual Trigger → Generate Data → Store in Google Sheets

---

## 🛠️ Tech Stack

* n8n (Workflow Automation Tool)
* Node.js
* Google Sheets API
* OAuth 2.0 Authentication

---

## ⚙️ Setup Instructions

### 1. Install Node.js

Download from: https://nodejs.org

### 2. Install n8n

```bash
npm install n8n -g
```

### 3. Start n8n

```bash
n8n start
```

### 4. Open n8n UI

```
http://localhost:5678
```

---

## 🧩 Workflow Steps

1. **Manual Trigger Node**

   * Starts the workflow execution

2. **Set Node**

   * Generates a message:

   ```
   Hello Khushboo
   ```

3. **Google Sheets Node**

   * Appends data to a Google Sheet
   * Stores:

     * Name
     * Message

---

## 📊 Google Sheets Structure

| Name     | Message        |
| -------- | -------------- |
| Khushboo | Hello Khushboo |

---

## 📸 Screenshots
<img width="1848" height="967" alt="Screenshot 2026-04-18 235230" src="https://github.com/user-attachments/assets/ccc4cd2f-a351-465d-a1e2-33f66eb1aab1" />



### 🔹 Google Sheets Result

---

## ▶️ How to Run

1. Import the workflow JSON into n8n
2. Connect your Google account (OAuth setup)
3. Click **Execute Workflow**
4. Check Google Sheets for stored data

---

## 🎯 Features

* Beginner-friendly automation workflow
* Google Sheets integration
* Secure OAuth authentication
* Real-time data processing

---

## 🔮 Future Improvements

* 📧 Gmail automation (auto-read emails)
* 🤖 AI-based email classification
* 🔔 Notifications via Telegram/Slack
* 📊 Dashboard for data visualization

---

## 🧠 Learning Outcomes

* Understanding workflow automation
* Hands-on with n8n nodes
* API integration using Google services
* OAuth authentication setup

---

## 💼 Resume Highlight

> Built an automated workflow using n8n to process and store structured data in Google Sheets using OAuth-secured API integration.

---

## 📌 Conclusion

This project demonstrates how automation tools like n8n can simplify repetitive tasks and integrate multiple services efficiently with minimal coding.

---

