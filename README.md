# CometChat UI Kit Integration – Internship Task

This repository contains my submission for the **CometChat Internship Task**, where I explored the CometChat dashboard, configured and implemented the React UI Kit, tested the documentation, and reported real-world usability findings.

---

## 🔹 Project Overview

- **Technology Used:** React  
- **Product Selected:** Chat & Messaging  
- **UI Kit Type:** React Pre-Assembled UI Kit  
- **Purpose:** Evaluation of CometChat SDK, UI Kit Builder, and Developer Experience  

---

## 🔹 Task Objectives Completed

✅ Signed up using Gmail with `+test` format  
✅ Created a CometChat application  
✅ Explored the Dashboard  
✅ Located and configured the UI Kit Builder  
✅ Downloaded and implemented the React UI Kit  
✅ Successfully ran the project locally  
✅ Sent and received messages  
✅ Noted real usability and reliability issues  
✅ Documented findings in a professional PDF  

---

## 🔹 Implementation Summary

- UI Kit was added into a new React project using VS Code
- Dependencies were installed successfully
- Application ran locally on `localhost`
- Login with valid UID worked (example user: George Abraham)
- Pre-existing users were visible
- Group and one-to-one chats worked correctly
- Messages were sent and received successfully
- Confirmation email was received after first chat message

---

## 🔴 Major Issue Observed (Real Bug)

### Issue: Message does not auto-send after network reconnection

**Expected:**  
If internet disconnects while sending a message, it should automatically send after reconnection.

**Actual:**  
After internet fluctuation, the message was not delivered. The page had to be refreshed and the message was manually retyped and resent.

**Impact:**
- Message loss
- User confusion
- Duplicate effort

**Suggested Improvement:**
- Offline message queue
- Auto retry after reconnection
- Network status indicators

---

## 📸 Screenshots

### 1. Chat UI
[Chat UI](assets/screenshots/chat-ui.png)

### 2. Users List
[Users](assets/screenshots/users-list.png)

### 3. Message Sent
[Message](assets/screenshots/message-sent.png)

---

## 🎥 Demo Video

👉 Screen Recording of Running Application:  
[video:](https://github.com/mhsanjunaid-dot/my_project/raw/main/assets/video/cometchat-ui-demo.mov
)

---

## 📄 Report Document

A detailed PDF report containing:
- Dashboard findings
- UI Kit Builder evaluation
- Documentation review
- Implementation experience
- Bugs, friction points & suggestions  

✅ Included in internship email submission.

---

## ▶️ How to Run This Project

```bash
npm install
npm run dev

Then open:
http://localhost:5173
