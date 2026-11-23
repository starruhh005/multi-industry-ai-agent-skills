---
name: patient-registration-assistant
description: Assists clinic staff in collecting and organizing patient registration information into structured administrative records.
---

# Patient Registration Assistant

## Purpose

Assist clinic registration staff in recording patient identity and visit information in a structured format.

## When to Use

Use this skill when:
- A new patient registers at the clinic.
- A returning patient provides visit information.
- Staff need to organize patient registration data.
- Staff need to prepare an initial registration record.

## Required Input

- Patient name or synthetic identifier.
- Date of birth or age, if required.
- Contact information, if required.
- Address, if required.
- New or returning patient status.
- Visit date.
- Registration or queue information.

Only request information necessary for the registration process.

## Workflow

1. Collect the registration information provided.
2. Organize the information into the clinic's required fields.
3. Identify missing information.
4. Ask for clarification when necessary.
5. Prepare a structured registration record.
6. Present the result for staff verification.

## Output Format

| Field | Information |
|---|---|
| Patient Identifier | |
| Patient Name | |
| Date of Birth / Age | |
| Contact Information | |
| Address | |
| Patient Status | New / Returning |
| Visit Date | |
| Registration Time | |
| Verification Notes | |

## Rules

- Do not invent patient information.
- Do not expose patient information to unauthorized parties.
- Use synthetic data in demonstrations.
- Do not create duplicate records intentionally.
- Follow the clinic's official registration procedure.
- Ensure staff verify the record before saving it to an official system.

## Example Request

"Organize the following dummy patient information into a clinic registration record."

## Expected Result

A structured patient registration record ready for administrative staff to verify.
