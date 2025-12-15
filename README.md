# Invoice.ge — Case Study (Private Code, Sold)

Invoice.ge is a web app for creating and managing invoices (clients, line items, totals, and invoice statuses).
This repo is a public case study (core code may be private), focused on architecture + features shipped.

## What I shipped
- **rs.ge integration**
  - Integrated external API flows and handled responses + edge cases.
- **SMS sending (end-to-end)**
  - Backend: implemented SMS sending service + validation/error handling.
  - Frontend: added user-facing triggers, loading states, and success/error feedback.
- **Notifications**
  - Built notification flows for key events (e.g., invoice status updates, reminders).
- **Quality / maintenance**
  - Fixed bugs, formatting issues, and improved reliability across common user paths.

## Why this matters
This project demonstrates real-world web development work:
integrations, user-facing flows, and shipping features with attention to detail.

## Tech stack
- Frontend: Next.js / React / TypeScript (edit if needed)
- Styling: (Tailwind / CSS Modules / etc.)
- Backend: (Node.js / Next.js API routes / etc.)
- Database: (Postgres / Supabase / Firebase / etc.)
- Integrations: rs.ge
- Messaging: SMS provider (Twilio / etc.)
- Deployment: (Vercel / other)

## Architecture (high level)
- UI (Next.js) renders invoice dashboard + forms
- Backend/API handles invoice CRUD + integrations + messaging
- Database stores users/clients/invoices/status history
- Notifications triggered on invoice events


## My role
- Owned the rs.ge integration implementation
- Implemented SMS flows on backend + frontend
- Built notifications and shipped multiple product improvements

## Contact
- LinkedIn: [here](https://www.linkedin.com/in/zhana-jikia-b9648a196/)
- Email: <janejikia@gmail.com>
