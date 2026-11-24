# Multi-Industry AI Agent Skills

## Project Overview

This repository contains a collection of AI Agent skill designs developed for five internship case studies across different industries and departments.

The project identifies repetitive administrative tasks that can be supported by AI Agents and provides structured skill instructions for each specialized agent.

The main goal is to demonstrate how AI Agents can assist employees in improving administrative efficiency, organizing information, processing documents, preparing reports, and reducing repetitive manual work.

## Case Studies

### 1. Government Administration — GovAssist

An AI Agent designed to assist local government office administration.

**Main capabilities:**
- Incoming letter processing
- Official letter drafting
- Document classification
- Meeting minutes summarization
- Administrative report generation
- Government service FAQ assistance

### 2. Clinic Registration & Anamnesa — ClinicFlow

An AI Agent designed to support clinic registration and initial patient information collection.

**Main capabilities:**
- Patient registration assistance
- Registration data validation
- Initial anamnesa interview assistance
- Patient complaint summarization
- Clinic visit recaps
- Clinic information assistance

*ClinicFlow is intended for administrative support and initial information collection, not medical diagnosis or treatment decisions.*

### 3. Digital Marketing Agency — MarketMate

An AI Agent designed to support digital marketing activities, content preparation, and campaign administration.

**Main capabilities:**
- Marketing brief analysis
- Audience persona building
- Content calendar planning
- Social media copywriting
- Content repurposing
- Hashtag and keyword assistance
- Campaign performance analysis
- Marketing report generation

### 4. Palm Oil Company HRD — PalmHR

An AI Agent designed to support Human Resources administrative activities in a palm oil company.

**Main capabilities:**
- Employee data validation
- Attendance recapitulation
- Recruitment document screening
- HR document organization
- Leave and permission administration
- HR letter drafting
- Employee FAQ assistance
- Monthly HR report generation

### 5. Banking Credit Administration — CreditMate

An AI Agent designed to support repetitive administrative tasks in credit application processing.

**Main capabilities:**
- Credit application intake
- Credit document checklist
- Document data extraction
- Applicant profile summarization
- Document consistency checking
- Missing document notification drafting
- Application status tracking
- Credit administration reporting

*CreditMate supports administrative document processing and does not make independent credit approval, rejection, or credit risk decisions.*

## Repository Structure

```text
multi-industry-ai-agent-skills/
│
├── government-administration/
│   ├── agent.md
│   ├── jobdesk-analysis.md
│   └── skills/
│
├── clinic-registration/
│   ├── agent.md
│   ├── jobdesk-analysis.md
│   └── skills/
│
├── digital-marketing/
│   ├── agent.md
│   ├── jobdesk-analysis.md
│   └── skills/
│
├── palm-oil-hr/
│   ├── agent.md
│   ├── jobdesk-analysis.md
│   └── skills/
│
├── bank-credit/
│   ├── agent.md
│   ├── jobdesk-analysis.md
│   └── skills/
│
└── README.md
```

Each case study contains:

- `agent.md` — agent overview, objectives, workflow, capabilities, limitations, and human oversight.
- `jobdesk-analysis.md` — jobdesk analysis, repetitive activities, and potential AI Agent support.
- `skills/` — specialized skill instructions organized into individual folders, each containing a `SKILL.md` file.

## Project Scope

This repository focuses on AI Agent skill definitions and workflow design. The skills describe how agents should handle specific tasks, what inputs they require, what procedures they follow, and what outputs they produce.

Actual automation, such as reading external databases, sending emails, processing uploaded documents, or updating company systems, requires additional tools, integrations, permissions, and implementation.

## Responsible AI and Human Oversight

The agents are designed to assist human workers rather than fully replace professional judgment.

- Important decisions remain under authorized human supervision.
- AI must not fabricate missing information.
- Sensitive data must be protected.
- Public demonstrations should use synthetic or fictional data.
- Outputs must be verified before being used for official purposes.
- Each agent must respect the limitations of its industry and assigned role.

## Project Objectives

- Identify repetitive work across different industries.
- Design specialized AI Agent skills for administrative tasks.
- Demonstrate practical AI applications in workplace environments.
- Improve workflow efficiency and information organization.
- Promote responsible AI usage with human oversight.

## Author

Created as an academic project exploring AI Agent skill design and applications across multiple industries.
