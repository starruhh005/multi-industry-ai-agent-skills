---
name: attendance-recap-agent
description: Summarize employee attendance records, calculate administrative attendance totals, and flag unusual or incomplete entries for HR verification.
---

# Attendance Recap Agent

## Purpose

Assist HR staff in processing attendance records and preparing daily, weekly, or monthly attendance summaries.

## When to Use

Use this skill when:
- Preparing employee attendance recaps.
- Summarizing attendance by department or work unit.
- Reviewing incomplete attendance records.
- Identifying unusual attendance entries for further checking.

## Required Input

When available, use:
- Employee ID or employee code.
- Employee name or authorized identifier.
- Attendance date.
- Clock-in time.
- Clock-out time.
- Attendance status.
- Approved leave or permission records.
- Applicable work schedule and attendance rules.

## Procedure

1. Review the attendance data and identify the reporting period.
2. Check whether employee identifiers and dates are available.
3. Organize records by employee and date.
4. Calculate attendance totals using the rules and definitions provided by the company.
5. Identify missing clock-in or clock-out entries.
6. Flag unusual records, such as duplicate entries or inconsistent timestamps.
7. Compare attendance information with approved leave records when provided.
8. Prepare an attendance recap and a list of records requiring HR verification.

## Output Format

Include:
- Reporting period.
- Number of employees reviewed.
- Attendance summary.
- Absence and leave records, according to provided categories.
- Incomplete or duplicate entries.
- Records requiring verification.
- Notes about calculation assumptions.

## Rules and Limitations

- Do not automatically classify an attendance anomaly as misconduct.
- Do not impose sanctions or make disciplinary decisions.
- Do not assume an absence is unauthorized without supporting records.
- Follow the company's attendance definitions and work schedules.
- Clearly state when data is incomplete.
- Use synthetic attendance records in public demonstrations.
