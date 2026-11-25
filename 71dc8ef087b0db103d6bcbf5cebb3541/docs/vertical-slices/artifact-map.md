# Artifact map

This map is a developer view only. It does not move generated ServiceNow files.

## Step 1 — Resume intake and parsing

| Concern | Generated artifact |
|---|---|
| Canonical Gemini parser | `update/sys_script_include_dc8e36f08738db103d6bcbf5cebb35a8.xml` |
| Parse orchestration and status writes | `update/sys_script_f3de32348738db103d6bcbf5cebb35e8.xml` |
| Pending trigger from PDF attachment insert | `update/sys_script_c2f4a0d887b0db103d6bcbf5cebb3502.xml` |
| Upload widget, PDF-only validation, status display | `update/sp_widget_278a9a308734db103d6bcbf5cebb35ea.xml` |
| Gemini API key property | `update/sys_properties_5e9cfabc87f4db103d6bcbf5cebb3536.xml` |
| Gemini model property | `update/sys_properties_b7e1c0f887b0db103d6bcbf5cebb3501.xml` |
| Gemini endpoint override property | `update/sys_properties_a8f2d1e887b0db103d6bcbf5cebb3506.xml` |
| Profile fields | `dictionary/x_2311790_skills_0_student_profile.xml` |
| Profile field definitions | `update/sys_dictionary_x_2311790_skills_0_student_profile_*.xml` |
| Parse status choices | `update/sys_choice_x_2311790_skills_0_student_profile_u_parse_status.xml` (copied from `author_elective_update/` so `update/`-only promotion includes them) |
| Internal field hidden from default form | `update/sys_ui_section_ea956ab08774db103d6bcbf5cebb35c5.xml` |
| Internal field hidden from default list | `update/sys_ui_list_x_2311790_skills_0_student_profile_null.xml` |
| Disabled broken flow | `update/sys_hub_flow_6049eef88774db103d6bcbf5cebb3569.xml` |
| Deleted unfinished parser | `update/sys_script_include_4e06baf087f4db103d6bcbf5cebb3505.xml` |
| Deleted unused REST message | `update/sys_rest_message_8a66b63487f4db103d6bcbf5cebb353c.xml` and related function/header files |

## Step 2 — Structured skills extraction

| Concern | Generated artifact |
|---|---|
| Structured Gemini parser | `update/sys_script_include_dc8e36f08738db103d6bcbf5cebb35a8.xml` |
| Structured skills writer | `update/sys_script_include_f100000e87b0db103d6bcbf5cebb350e.xml` |
| Structured parse orchestration | `update/sys_script_f3de32348738db103d6bcbf5cebb35e8.xml` |
| Skill master schema | `dictionary/x_2311790_skills_0_skill_master.xml` |
| Student skill schema | `dictionary/x_2311790_skills_0_student_skill.xml` |
| Profile schema with education/years/projects | `dictionary/x_2311790_skills_0_student_profile.xml` |
| New field definitions | `update/sys_dictionary_x_2311790_skills_0_*.xml` |
| New choice definitions | `update/sys_choice_x_2311790_skills_0_*.xml` |
| Corrected cap rule | `update/sys_script_2a355e3487f0db103d6bcbf5cebb3536.xml` |
| Read-only parsed skills UI | `update/sp_widget_278a9a308734db103d6bcbf5cebb35ea.xml` |
| Table roles | `update/sys_user_role_*skill*.xml` |

## Step 3 — Embeddings and matching (planned)

| Concern | Generated artifact |
|---|---|
| Profile embedding field | `dictionary/x_2311790_skills_0_student_profile.xml` |
| Internship embedding and requirements | `dictionary/x_2311790_skills_0_internship.xml` |
| Application score and rationale | `dictionary/x_2311790_skills_0_internship_application.xml` |

## Step 4 — Recruiter portal and workflow (planned)

| Concern | Generated artifact |
|---|---|
| Accept Applicant email flow | `update/sys_hub_flow_0b76127487f0db103d6bcbf5cebb35b8.xml` |
| Internship and application tables | `dictionary/x_2311790_skills_0_internship*.xml` |
| Portal pages | `update/sp_page_*.xml` |
| Resume upload widget | `update/sp_widget_278a9a308734db103d6bcbf5cebb35ea.xml` |

## Step 5 — RBAC and platform hardening (planned)

| Concern | Generated artifact |
|---|---|
| Roles | `update/sys_user_role_*.xml` |
| Table ACLs | `update/sys_security_acl_*.xml` |
| ACL role mappings | `update/sys_security_acl_role_*.xml` |
| Scope settings | `sys_app_71dc8ef087b0db103d6bcbf5cebb3541.xml` |
| Scope privileges | `update/sys_scope_privilege_*.xml` |
