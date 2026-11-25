# Step 4 — Recruiter portal and workflow

Status: planned, not implemented beyond the existing Accept Applicant email flow.

Planned work:

- Define the application lifecycle: `submitted`, `under_review`, `accepted`, `rejected`.
- Decide whether Approval Engine records are required.
- Build internship posting, ranked applicants, and accept/reject UI.
- Keep the existing Accept Applicant flow only if it matches the final lifecycle.
- Use a service identity for background matching and parsing-related writes.

Do not start this slice until matching output is stable.
