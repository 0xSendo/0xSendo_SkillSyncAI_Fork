# Step 5 — RBAC and platform hardening

Status: planned, not implemented.

Planned work:

- Replace table-wide ACLs with row-scoped conditions.
- Students see and edit only their own profile and skills.
- Org heads see only their own internships and applications.
- Add field ACLs for embeddings, parse internals, and raw resume output.
- Add attachment ACLs.
- Tighten scope settings and reduce broad global scriptable privileges.
- Build the role-aware portal page, including the requested `Hello + [role]` display.
- Reconcile orphaned portal instances and empty pages.

Step 1 only hid `embedding` from the default form and list and added a server-side role check in the upload widget. Full RBAC remains a later slice.
