# Step 2 — Structured skills extraction

Status: planned, not implemented.

Planned work:

- Extend the Gemini response schema with `skills`, `tools`, `education`, `experience_years`, and `projects`.
- Upsert normalized Skill Master rows.
- Upsert Student Skill rows with deduplication.
- Fix `Cap Student Skills` to query `x_2311790_skills_0_student_skill` instead of `u_student_skill`.
- Decide the cap/core-skill policy: parse up to 10, mark top 3 as core for matching.
- Add unique indexes on normalized Skill Master `name` and Student Skill `(u_profile, u_skill)`.

Do not start this slice until Step 1 passes the PDI test plan.
