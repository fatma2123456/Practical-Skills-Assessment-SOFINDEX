# Practical Skills Assessment for SOFINDEX

This repository contains the completed projects for the AI Automation Engineer practical skills assessment from SOFINDEX.

---

## 1. Mandatory Project:  Automated Warm Lead Generation Bot

This project demonstrates a bot designed to generate and qualify warm leads automatically.

### Deliverables:

*   **Video Demonstration:** **[https://github.com/fatma2123456/Practical-Skills-Assessment-SOFINDEX/blob/main/Mandatory%20Project/mandatory%20project%20video.mp4]**
*   **Blueprint/Code:** The workflow can be found in the `1_Warm_Lead_Generation_Bot` folder.

### Tools Used:
- n8n
- Google Sheets
- Google Gemini API
- Javascript

---

## 2. Optional Project: Telegram Voice-to-Task Workflow

I have chosen the **Telegram Voice-to-Task Workflow** as my optional project. This workflow acts as a personal assistant that captures a voice message from Telegram, transcribes it, extracts tasks, and creates them as new items in Notion.

### Deliverables:

*   **Video Demonstration:** **[https://github.com/fatma2123456/Practical-Skills-Assessment-SOFINDEX/blob/main/Telegram%20Voice-to-Task%20Project/Telegram%20Voice-to-Task.mp4]**
*   **n8n Blueprint (JSON):** The exported JSON for the n8n scenario is located in the `2_Telegram_Voice-to-Task` folder.

### Workflow Steps:

1.  **Trigger:** A Telegram bot listens for new voice messages.
2.  **Transcription:** The voice note is transcribed into text using the Google Gemini API.
3.  **Parsing:** The transcribed text is analyzed by Google Gemini to identify and extract individual to-do items into a structured JSON array.
4.  **Task Creation:** Each extracted item is added as a new page in a Notion database.

### Tools Used:

*   n8n
*   Telegram
*   Google Gemini API
*   Notion

---

**Submitted by:** Fatma Elzhraa Ahmed
