

# The Simplest Bookkeeper

**Log sales. Track expenses. Just talk.**

The Simplest Bookkeeper is a voice-first bookkeeping assistant designed for informal business owners in Africa. It lets users record sales and expenses on the go—no apps, no forms, no friction. Just speak, and your records are done.

## ✨ What It Does

* **Voice-First Input**: Users send a voice note via WhatsApp.
* **AI Transcription + Parsing**: We transcribe and extract the transaction type (sale/expense), amount, and category.
* **Auto Logging**: The transaction is saved automatically to a Google Sheet or Firestore DB.
* **Real-Time Feedback**: Users get confirmation and a summary of what was logged.

## 🧠 Why It Exists

Most bookkeeping tools are made for accountants. This one is made for real people running shops, stalls, or services who just need a simple way to track cash flow.

## 💡 Key Features

* Voice-based data entry (via WhatsApp or chat UI)
* Auto-categorization of transactions
* Simple summaries via chat
* Offline-first mindset
* Works on low-end smartphones

## ⚙️ Tech Stack

* **Frontend**: WhatsApp UI + minimal web dashboard (optional)
* **Backend**: django
* **Transcription**: Whisper / Google Speech-to-Text
* **Data Store**: Google Sheets or Firestore
* **Messaging Interface**: Twilio API for WhatsApp or WhatsApp Cloud API

#

## 🧪 Example Voice Input

> "I sold bread for 500 today."

System response:

> ✅ Sale of 500 logged under category **bread**.

## 🌍 Who It's For

* Street vendors
* Small shop owners
* Bus drivers
* Tailors, hairdressers, mechanics
* Anyone who says: “I don’t have time to do my accounts.”

## 🤝 Contributing

I welcome contributions! Whether it's improving transcription, refining category detection, or UX for summaries—PRs are open.

