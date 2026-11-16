# Taranga ERP

Single-page ERP for Taranga Enterprise: investors (opening balance), clients, monthly billing (OTC, MRC, link quantity),
purchases, vendors, costs, stock in/out, ledger by payment channel (Cash, bKash, Rocket, Nagad, Bank Transfer),
reports (CSV and Excel) and a dashboard.

- `taranga-erp.html` is the whole app (HTML, CSS and JavaScript in one file). It is published as a claude.ai Artifact, which supplies the shared database.
- Access: **Admin** (Share level Editor) can change everything. **Guest** (Share level Viewer) is view-only. The database rejects writes from Guests.
- Backup: Reports page, "Download backup (JSON)". Restore: Reports page, "Restore from backup" (Admin only, merge or replace).
- This repository holds the code only. Business data lives in the artifact's database, so keep downloading backups.
