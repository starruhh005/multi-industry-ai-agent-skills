---
name: registration-validation
description: Checks clinic registration information for missing fields, inconsistent entries, and administrative completeness.
---

# Registration Validation

## Purpose

Help clinic staff check the completeness and consistency of patient registration data.

## When to Use

Use this skill when:
- A registration form has been completed.
- Staff need to identify missing information.
- Patient administrative data needs checking.
- A registration record needs to be reviewed before submission.

## Required Input

- Patient registration form.
- Required registration fields.
- Clinic registration checklist.
- Available patient administrative information.

## Workflow

1. Review the provided registration data.
2. Compare the information with the required fields.
3. Identify missing entries.
4. Identify inconsistent or unclear information.
5. Prepare a validation checklist.
6. Ask staff to verify any questionable information.

## Output Format

| Field | Status | Notes |
|---|---|---|
| Patient Name | Complete / Missing | |
| Date of Birth / Age | Complete / Missing | |
| Contact Information | Complete / Missing | |
| Address | Complete / Missing | |
| Visit Information | Complete / Missing | |
| Other Required Fields | Complete / Missing | |

**Overall Status:** Complete / Incomplete / Requires Verification

## Rules

- Do not guess missing information.
- Do not modify patient data without authorization.
- Distinguish missing information from inconsistent information.
- Do not reject a patient based solely on an AI-generated validation result.
- Follow the clinic's registration requirements.

## Example Request

"Check this dummy registration form and identify which required fields are incomplete."

## Expected Result

A registration validation checklist that helps staff complete administrative records accurately.
