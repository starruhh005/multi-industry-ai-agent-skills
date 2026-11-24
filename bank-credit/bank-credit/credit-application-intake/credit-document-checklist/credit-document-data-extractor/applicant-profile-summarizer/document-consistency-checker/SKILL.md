---
name: document-consistency-checker
description: Compare information across credit application documents and identify inconsistencies for human verification.
---

# Document Consistency Checker

## Purpose

Assist credit administration staff in comparing information across credit application documents to identify potential inconsistencies, mismatched entries, or missing details that require further verification.

## When to Use

Use this skill when:
- Comparing applicant information across multiple documents.
- Reviewing application forms and supporting documents.
- Checking consistency of dates, names, addresses, or financial figures.
- Preparing document review notes.

## Required Input

When available, use:
- Credit application form.
- Applicant identity documents.
- Employment or business documents.
- Income supporting documents.
- Bank-provided verification checklist.
- Comparison criteria or administrative procedures.

## Procedure

1. Identify the documents provided for comparison.
2. Extract the relevant fields from each document.
3. Compare the same fields across the available documents.
4. Identify values that match, differ, or cannot be compared.
5. Record the document sources for each finding.
6. Distinguish confirmed differences from possible extraction errors.
7. Prepare a structured inconsistency report.
8. Forward the findings to authorized bank personnel for review.

## Output Format

| Field Compared | Document A | Document B | Result | Notes |
|---|---|---|---|---|
| Applicant name | Extracted value | Extracted value | Match / Difference / Needs Review | Supporting details |

Include a summary of:
- Fields that match.
- Potential inconsistencies.
- Missing information.
- Unreadable information.
- Items requiring manual verification.

## Rules and Limitations

- Do not automatically declare a discrepancy to be fraud.
- Do not assume a difference is intentional.
- Do not modify original document data.
- Do not invent values to resolve discrepancies.
- Clearly identify the source of each comparison.
- Protect confidential applicant information.
- Use synthetic documents in public demonstrations and testing.
