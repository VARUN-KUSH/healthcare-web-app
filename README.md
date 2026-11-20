# healthcare-web-app

**Counterline** – clickable Stage 1 prototype of a staff task dashboard for a community pharmacy AI phone assistant (Retell AI + Twilio).

All data is fictional demo data (phone numbers use the Ofcom 07700 900xxx drama range).

## What the demo shows
- **Staff sign-in with two-step verification** (pick any demo staff member; any 6 digits work)
- **Live task list** – patient, request type, received time, deadline, status (new / in progress / overdue / done); updates without refreshing, new patient calls arrive automatically
- **One-tap actions** – Ready (texts the patient via Twilio and closes the task, with undo), Called back, Add note, Reopen
- **Call log** – Retell AI summary, outcome, transcript and recording player
- **Retell webhook** – `call_analyzed` deliveries with payloads, creating tasks
- **Audit trail** – every sign-in, record view and change by named staff, hash-chained
- **Reports** – calls by reason, tasks closed on time, calls by hour
- Works on desktop and phone, light and dark mode

## Run locally
Open `index.html` in a browser. No build step.
