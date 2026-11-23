---
name: incoming-letter-processor
description: Processes incoming correspondence by extracting, organizing, and summarizing important letter information for government office administration.
---

# Incoming Letter Processor

## Purpose

Assist administrative staff in recording and organizing incoming letters received by a local government office.

## When to Use

Use this skill when staff need to:
- Record incoming correspondence.
- Extract important information from letters.
- Summarize the contents of incoming letters.
- Prepare an incoming correspondence register.

## Required Input

The agent should request or identify:

- Letter number.
- Letter date.
- Date received.
- Sender or institution.
- Subject.
- Main contents.
- Attachments, if any.

If some information is unavailable, mark it as "Not provided" rather than inventing it.

## Workflow

1. Read the provided letter or text.
2. Identify the sender and letter details.
3. Extract the letter number, date, and subject.
4. Summarize the main purpose of the letter.
5. Identify any requested action or deadline stated in the letter.
6. Organize the information into a structured record.
7. Mark missing information for staff verification.

## Output Format

| Field | Information |
|---|---|
| Letter Number | |
| Letter Date | |
| Date Received | |
| Sender | |
| Subject | |
| Main Summary | |
| Requested Action | |
| Deadline | |
| Attachments | |
| Verification Notes | |

## Rules

- Never fabricate letter information.
- Preserve the original meaning of the letter.
- Do not issue official dispositions.
- Do not approve or reject correspondence.
- Flag unclear or incomplete information.
- Keep confidential documents protected.

## Example Request

"Please extract the important information from this incoming letter and prepare an administrative registration record."

## Expected Result

A structured incoming letter record ready for administrative staff to review and enter into the official correspondence system.
