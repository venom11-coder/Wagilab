# 🧠 Wagilab — AI-Powered Personal Activity Assistant

A cross-platform agentic personal assistant that automatically tracks, organizes, and summarizes a user's daily activity across email, calendar, and location — powered by large language model APIs.

> **Research Collaboration** — Built in collaboration with a researcher at **Western University**. This repository contains my personal contributions to the project's backend integrations and API pipeline.

> ⚠️ **Project Status: Archived** — This project is no longer actively maintained. The code is preserved here as a reference for the integrations developed.

---

## 💡 What It Does

Wagilab connects to a user's existing productivity tools — Gmail, Google Calendar, Microsoft accounts, and location services — to build a unified picture of what they did throughout the day. An LLM then processes this data to generate structured daily and weekly summaries, helping users reflect on their time and productivity.

---

## 🗂 My Contributions

This repo contains the backend modules I personally developed for the project:

| Module | Description |
|--------|-------------|
| `GmailAPI` | Gmail integration — fetches and parses user emails via Google API |
| `email_sorting_by_day_by_week` | Sorts and categorizes email activity by day and week for LLM summarization |
| `Calender_Integration` | Google Calendar integration — reads events and schedules |
| `Google_Login` | OAuth 2.0 Google authentication flow |
| `Microsoft_Auth` | Microsoft account authentication integration |
| `facebook_login` | Facebook OAuth login integration |
| `Map_Integration` | Web-based location tracking and map integration |
| `Maps_Android` | Android-specific location and maps integration |
| `get_maclocation` | macOS location detection module |

---

## 🛠 Tech Stack

| Layer | Technology |
|-------|-----------|
| Auth | Google OAuth 2.0, Microsoft Auth, Facebook Login |
| Email | Gmail API |
| Calendar | Google Calendar API |
| Location | Google Maps API (Web + Android), macOS Location Services |
| AI/LLM | Large Language Model API integration |
| Platform | Cross-platform (Web, Android, macOS) |

---

## 🔑 Key Technical Work

- Implemented **multi-provider OAuth** flows supporting Google, Microsoft, and Facebook authentication in a single unified pipeline
- Built **Gmail parsing and sorting logic** that categorizes emails by day and week for structured LLM input
- Integrated **Google Calendar API** to extract scheduling context alongside email and location data
- Developed **cross-platform location modules** for both Android and macOS to support activity tracking
- Designed the data pipeline to feed structured context into an LLM for automated daily activity summarization

---

## ⚙️ Setup (for reference)

Since the project is archived, full setup is not actively supported. However, each module is self-contained and can be referenced independently.

Each integration requires its own API credentials:

```
GOOGLE_CLIENT_ID=your_google_client_id
GOOGLE_CLIENT_SECRET=your_google_client_secret
MICROSOFT_CLIENT_ID=your_microsoft_client_id
FACEBOOK_APP_ID=your_facebook_app_id
MAPS_API_KEY=your_google_maps_key
```

---

## 👨‍💻 Developer

**Aman Sharma** — CS Student @ Western University
[LinkedIn](https://www.linkedin.com/in/aman-sharma-086310271/) · [Portfolio](https://aman-portfolio-three-xi.vercel.app/) · [GitHub](https://github.com/venom11-coder)

*Developed as part of a research collaboration at Western University.*
