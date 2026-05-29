# AI Appointment Booking Agent

Built a conversational AI agent for a client, 
embedded directly on their website, that automates 
appointment scheduling through natural language.
Visitors simply chat to check availability and book 
appointments — no manual back-and-forth needed.

## Demo
[Watch Demo Video](https://www.loom.com/share/6b64a4989553446fb6e5be8528893edf)

## Screenshots
<img width="1908" height="1098" alt="ai1" src="https://github.com/user-attachments/assets/946e9d31-73f8-4b73-b149-a6973018698c" />
<img width="1918" height="1068" alt="ai2" src="https://github.com/user-attachments/assets/79a81196-0207-4a18-ba2d-825df118bf61" />
<img width="1916" height="1093" alt="ai3" src="https://github.com/user-attachments/assets/116e84e1-eb0b-43de-9fda-df8afd4eb443" />
<img width="1206" height="679" alt="ai4" src="https://github.com/user-attachments/assets/e9ec76a4-bd76-498a-a45a-c2592ccc4659" />

## How It Works
1. User sends a booking request via the website chat
2. AI extracts the requested date and time
3. System checks Google Calendar availability in real time
4. AI responds with available time slots
5. User selects a preferred time to confirm booking

## Tech Stack
- n8n (workflow automation)
- OpenAI GPT (natural language understanding)
- Google Calendar FreeBusy API (availability checking)
- Simple Memory (conversation context)
- OAuth2 (secure authentication)

## Key Features
- Natural language booking via website chat
- Real-time Google Calendar availability checks
- Memory-enabled conversation flow
- Returns available time slots intelligently
- Fully automated end-to-end scheduling pipeline

## Result
When tested, the bot correctly identified that 
AI Workshop was fully available on May 30, 2026 
between 7:00 AM and 8:00 PM and communicated 
this naturally to the user.
