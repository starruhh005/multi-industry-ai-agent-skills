---
name: credit-document-data-extractor
description: Extract and structure information from credit application documents for administrative review.
---

# Credit Document Data Extractor

## Purpose

Assist credit administration staff in extracting relevant information from credit application documents and organizing it into structured administrative records.

## When to Use

Use this skill when:
- Extracting applicant information from application forms.
- Reviewing financial supporting documents.
- Transferring information into administrative summaries.
- Preparing structured records from submitted documents.

## Required Input

When available, use:
- Credit application forms.
- Applicant identity information.
- Employment or business information.
- Income information.
- Financial supporting documents.
- Document extraction instructions.
- Required data field templates.

## Procedure

1. Review the provided document or text.
2. Identify the document type.
3. Extract only information that is explicitly available.
4. Organize the extracted information into the requested fields.
5. Preserve original values, dates, units, and currency.
6. Mark unreadable or missing information as "Not available" or "Needs verification."
7. Identify fields that require manual confirmation.
8. Present the extracted data in a structured format.

## Output Format

Provide a table containing:

| Field | Extracted Information | Source Document | Verification Status |
|---|---|---|---|
| Field name | Extracted value | Document reference | Verified from text / Needs review |

Include a short summary of:
- Successfully extracted fields.
- Missing fields.
- Unreadable information.
- Potential extraction errors.
- Items requiring manual verification.

## Rules and Limitations

- Do not fabricate missing financial or personal information.
- Do not modify the original information.
- Do not assume OCR output is accurate.
- Preserve the original currency and measurement units.
- Clearly identify uncertain extracted values.
- Protect customer privacy.
- Use synthetic documents and financial information in public repository examples.
