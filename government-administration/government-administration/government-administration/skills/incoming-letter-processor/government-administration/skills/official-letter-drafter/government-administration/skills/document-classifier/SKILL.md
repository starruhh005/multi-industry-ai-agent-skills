---
name: document-classifier
description: Classifies government administrative documents based on their type, subject, date, and other available metadata.
---

# Document Classifier

## Purpose

Help administrative staff organize government office documents into appropriate categories.

## When to Use

Use this skill when staff need to:
- Classify incoming documents.
- Organize digital files.
- Group documents by subject or date.
- Prepare document archive indexes.
- Identify documents with incomplete metadata.

## Required Input

- Document name or title.
- Document content or description.
- Document date.
- Sender or originating department, if available.
- Document type.
- Existing archive categories, if available.

## Workflow

1. Read the document title and available content.
2. Identify the main subject.
3. Determine the most suitable document category.
4. Extract available metadata.
5. Suggest an appropriate archive folder or label.
6. Identify missing or unclear information.
7. Present the classification result for staff verification.

## Output Format

| Field | Result |
|---|---|
| Document Name | |
| Document Type | |
| Subject | |
| Document Date | |
| Originating Department | |
| Suggested Category | |
| Suggested Folder | |
| Missing Information | |

## Rules

- Do not change original document contents.
- Do not invent document metadata.
- Use the categories provided by the institution.
- If classification is uncertain, state the uncertainty.
- Do not delete or move official files without authorization.

## Example Request

"Classify these administrative documents based on their subject and date, then suggest suitable archive categories."

## Expected Result

A structured document classification list that helps staff organize administrative archives.
