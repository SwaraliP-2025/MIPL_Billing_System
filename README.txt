MIPL Billing & Payment Tracker - code package
=============================================

1) standalone-single-user.html
   - Plain HTML + CSS + JavaScript, no server, no installs.
   - Double-click to open in any browser (Chrome, Edge, Firefox).
   - Contains dummy data for the 5 sites. Your changes are saved in
     that browser only (localStorage). No logins, no file attachments.
   - Good for trying the idea or running it on one computer.

2) multi-user.html
   - Open with VS Code Live Server to use the tracker dashboard, invoices,
     payments, reports, audit log, and attachments.
   - Data is saved in this browser only (localStorage); it is not shared
     between users or devices. Clearing browser data removes saved records.
   - This local version has one Admin profile. Shared accounts and roles
     require a hosted authentication, database, and file-storage backend.
   - Use Projects to add/edit projects and configure payment methods.
     Projects appear in the new-invoice dropdown; payment methods appear
     when recording a payment. Existing invoices and receipts are preserved.

All names, amounts and clients are made-up demo data.
