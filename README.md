# Invoice.ge — Case Study (Private Code, Sold)

Invoice.ge is a web app for creating and managing invoices (clients, line items, totals, and invoice statuses).
This repo is a public case study (core code may be private), focused on shipped features + architecture. (Now part of TBC Bank)

## What I shipped
- **rs.ge integration**
  - Integrated external API flows and handled responses + edge cases.
- **SMS sending (end-to-end)**
  - Backend: implemented SMS sending service + validation/error handling.
  - Frontend: added user-facing triggers, loading states, and success/error feedback.
- **Notifications**
  - Built notification flows for key events (invoice updates / reminders).
- **Testing**
  - Wrote **unit tests** for core logic.
  - Added **Cypress E2E tests** for critical frontend flows.
- **Quality / maintenance**
  - Fixed bugs, broken links, formatting issues, and improved reliability.

## Tech stack
- Frontend: Next.js / React / TypeScript
- Styling: (Tailwind / CSS Modules / etc.)
- Backend: Node.js / Next.js API routes
- Database: **MongoDB**
- Integrations: rs.ge
- Messaging: SMS provider (Twilio)
- Testing: Unit tests (Jest/Vitest) + **Cypress (E2E)**

## Architecture (high level)
- Next.js UI renders dashboard + invoice editor
- API layer handles invoice CRUD, rs.ge requests, SMS, and notification triggers
- MongoDB stores users/clients/invoices/status + notification records
- Automated tests cover both logic (unit) and user flows (Cypress)

## My role
- Owned the rs.ge integration implementation
- Implemented SMS flows on backend + frontend
- Built notifications
- Added unit tests + Cypress E2E tests
- Shipped multiple product improvements in a production-style workflow

## Contact
- LinkedIn: [here](https://www.linkedin.com/in/zhana-jikia-b9648a196/)
- Email: <janejikia@gmail.com>
