MIPL Billing & Payment Tracker - code package
=============================================

1) standalone-single-user.html
   - Plain HTML + CSS + JavaScript, no server, no installs.
   - Double-click to open in any browser (Chrome, Edge, Firefox).
   - Contains dummy data for the 5 sites. Your changes are saved in
     that browser only (localStorage). No logins, no file attachments.
   - Good for trying the idea or running it on one computer.

2) multi-user-claude-hosted.html
   - The full version: logins/roles, shared live data, file attachments,
     bank-match ticks, follow-ups, reports, audit log.
   - It uses claude.ai's built-in services (user, db, assets, downloads),
     so it only works when published as a claude.ai Artifact.
     Opened directly from this file it will show a "sign in" message.
   - To move it to your own hosting, the claude.ai services must be replaced:
       user  -> your login system (e.g. Firebase Auth / company SSO)
       db    -> a database (e.g. Firestore, Supabase, PostgreSQL + API)
       assets-> file storage (e.g. S3, Supabase Storage)
     The screens and calculations (function calc) can be reused as they are.

All names, amounts and clients are made-up demo data.
