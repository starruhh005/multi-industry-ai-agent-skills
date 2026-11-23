---
name: patient-complaint-summarizer
description: Summarizes patient-reported complaints into concise and structured notes without changing their original meaning.
---

# Patient Complaint Summarizer

## Purpose

Help clinic staff summarize lengthy patient complaints into clear administrative and clinical-support notes.

## When to Use

Use this skill when:
- A patient provides a lengthy complaint.
- Staff need to organize patient statements.
- Initial complaint information needs to be transferred to medical personnel.

## Required Input

- Patient's original complaint.
- Duration of the complaint, if provided.
- Related symptoms reported by the patient.
- Additional information provided during registration.

## Workflow

1. Read the patient's original statement.
2. Identify the main complaint.
3. Identify the duration and other details explicitly mentioned.
4. Summarize the statement without changing its meaning.
5. Separate reported facts from information that remains unclear.
6. Present the summary for staff verification.

## Output Format

**Main Complaint:**  

**Duration:**  

**Other Reported Symptoms:**  

**Additional Information:**  

**Information Requiring Clarification:**  

## Rules

- Do not add symptoms that were not reported.
- Do not convert a complaint into a medical diagnosis.
- Preserve important details from the original statement.
- Use neutral and clear language.
- Mark unclear information for clarification.
- Refer urgent information to qualified clinic staff.

## Example Request

"Summarize this dummy patient's complaint into a short structured note without making a diagnosis."

## Expected Result

A concise and accurate summary of the patient's reported complaint for review by medical personnel.
