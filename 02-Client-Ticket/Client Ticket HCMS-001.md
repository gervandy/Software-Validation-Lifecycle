# Client Ticket

---

## Ticket Information

| Field | Value |
|-------|-------|
| Ticket ID | HCMS-001 |
| Project | Healthcare Case Management System |
| Reported By | ABC Healthcare |
| Reported Date | 20 June 2026 |
| Environment | Production |
| Severity | High |
| Priority | High |
| Status | Assigned to Development |

---

## Issue Summary

Duplicate medication records are generated when exporting a healthcare case into CSV format.

---

## Business Impact

- Medication report is inaccurate.
- Healthcare staff must manually verify exported data.
- Potential risk of incorrect patient documentation.
- Reduced client confidence.

---

## Steps to Reproduce

1. Login to HCMS.
2. Navigate to **Case List**.
3. Open an existing healthcare case.
4. Click **Export Case**.
5. Download the CSV file.
6. Observe duplicated medication records.

---

## Expected Result

Each medication should appear only once in the exported CSV.

---

## Actual Result

Some medications are duplicated multiple times.

---

## Attachments

- Exported CSV sample
- Screenshot of duplicated medication rows

---

## Initial Investigation

Client confirmed the issue occurs consistently across multiple healthcare cases.

Issue reproduced in Production.
