# 🧓💊 TataAI — Elderly Medicine Reminder App

**TataAI** is a heartfelt, intelligent medicine reminder system designed especially for the elderly. With a gentle voice alert to remind seniors to take their medication, it ensures timely action. If there's no response from the elder within a specified time, TataAI automatically sends a WhatsApp message to their caretakers, children, or grandchildren — bringing love, care, and tech together.

## 🌟 Core Features

### 🎤 Voice-Based Alerts
- Sends **voice reminders** through speakers or connected devices at scheduled times.
- Friendly tone designed for elderly ears — clear and reassuring.

### 🧠 Inactivity Detection
- Waits for a predefined **response window** (e.g., a touch, button press, or verbal reply).
- If no response is detected within that time, the system considers the alert **unacknowledged**.

### 📲 WhatsApp Escalation
- Automatically sends a **WhatsApp message** to the assigned caretaker(s), such as:
  > "tata hasn’t responded to her 8 PM medicine reminder. Please check in on him ❤️"
- Supports **multiple recipients** (children, grandchildren, home nurse, etc.)

### 🗓️ Smart Scheduling
- Custom medicine schedules: daily, alternate days, or specific dates.

- ## 💻 Tech Stack

| Layer         | Technology                        |
|---------------|------------------------------------|
| Backend       | Node.js / Express.js              |
| Messaging API | Twilio + WhatsApp Business API    |
| Voice Alerts  | Node.js + Text-to-Speech (TTS) Engines |
| Detection     | voice recognition 
| Database      |  Firebase     
