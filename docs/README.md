# Detailed Project Documentation

## HR Job Search Analytics Workflow

This document explains the purpose, structure, and outputs of the HR Job Search Analytics Workflow in more detail.

The public GitHub repository contains a sanitized demo version of the workflow. The private working version is more detailed and includes personal job-search configuration, resume fact-bank logic, scoring rules, optional live integrations, application material review logic, and structured output handling. These private elements were removed from the public version to protect personal information, API configuration, contact research, and real application records.

## Why I Built This

Today’s job market is highly competitive, especially for students and early-career candidates. A strong job search now requires more than submitting the same resume repeatedly.

A candidate needs to:

* Track roles clearly
* Understand role fit
* Compare opportunities
* Review ATS keyword alignment
* Prepare tailored application materials
* Identify useful networking targets
* Follow up consistently
* Avoid losing track of deadlines and next steps

I built this workflow to make that process more structured, data-informed, and intentional.

## Project Goal

The goal of this project is not to mass apply to jobs or replace human judgment.

The goal is to create a human-reviewed job-search system that helps organize opportunities, evaluate fit, prepare stronger application materials, and track next steps before applying.

## What the Workflow Supports

The full working version is designed to support the following areas:

### 1. Job Opportunity Tracking

The workflow captures job information and organizes it into a structured format. This helps compare roles instead of reviewing each job manually from scratch.

Example information includes:

* Company name
* Job title
* Location
* Employment type
* Job link
* Job description
* Date found
* Source
* Application status

### 2. Role-Fit Scoring

The workflow evaluates each job based on role relevance and fit.

The scoring logic considers areas such as:

* HR relevance
* Internship or entry-level fit
* Skills match
* Location or timing fit
* Application readiness
* Networking potential
* Job priority

This helps identify which roles deserve more attention.

### 3. ATS Keyword Alignment

The workflow reviews how well the resume and application materials align with the job description.

This includes checking for important HR and analytics-related keywords such as:

* HR operations
* Recruiting coordination
* Talent acquisition
* People analytics
* HRIS
* Onboarding
* Employee records
* Benefits
* Reporting
* Excel
* Power BI
* Tableau

The purpose is to improve alignment before applying, not to manipulate the process.

### 4. Resume Draft Support

The private working version can prepare tailored resume drafts based on verified experience and skills.

The workflow uses a resume fact-bank approach so that resume content stays grounded in real, approved experience.

The resume drafts are not submitted automatically. They are created for human review, editing, and final approval.

### 5. Cover Letter Draft Support

The workflow can prepare cover letter drafts based on the role, company, and selected resume angle.

These drafts are designed to give a starting point, not a final automatic submission.

Each cover letter still requires review, editing, and personalization before use.

### 6. Networking Research

The workflow helps organize networking research by identifying useful categories of people to look for, such as:

* Recruiters
* Talent acquisition partners
* HR business partners
* People operations contacts
* HR operations managers
* Early-career or university recruiters
* Current employees in similar HR roles

The purpose is to guide manual research and thoughtful outreach.

### 7. Outreach Draft Support

The workflow can prepare draft messages for networking.

These messages are designed for review before sending and are not sent automatically.

The goal is to make outreach more thoughtful, specific, and organized.

### 8. Application Action Queue

The workflow creates an action queue that helps organize next steps.

Example actions include:

* Review job description
* Check role-fit score
* Review ATS alignment
* Review resume draft
* Review cover letter draft
* Research networking targets
* Send manual outreach
* Apply after final review
* Follow up later

### 9. Daily Opportunity Summary

The workflow can summarize top opportunities and next actions in one place.

This helps reduce confusion and keeps the job search organized.

A daily summary may include:

* Top roles to review
* Highest-priority opportunities
* Resume draft status
* Cover letter status
* Networking status
* Follow-up reminders
* Application readiness notes

## Public Demo vs. Private Working Version

The uploaded workflow file in this repository is a sanitized demo version.

It does not include:

* Private job-search data
* Personal resume information
* API credentials
* Real contact information
* Real application records
* Private job-search configuration
* Automated sending
* Full live integration setup

The private working version contains more advanced logic and output handling, but those details are intentionally excluded from the public repository for privacy and safety.

## Human Review and Safety

This workflow is designed around a human-in-the-loop process.

It does not auto-apply to jobs.
It does not auto-send outreach messages.
It does not replace personal judgment.
It does not remove the need to review job descriptions carefully.

Every resume draft, cover letter draft, networking message, and application decision requires human review before use.

## Skills Demonstrated

This project demonstrates practical skills in:

* HR analytics
* Recruiting workflow design
* HR operations thinking
* Job-fit analysis
* ATS keyword alignment
* Resume review process design
* Workflow automation
* Process improvement
* Data-driven decision support
* Human-in-the-loop workflow design
* Documentation and portfolio presentation

## Tools and Concepts Used

The project uses or demonstrates:

* n8n workflow automation
* Google Sheets-style tracking structure
* Job scoring logic
* Resume fact-bank design
* Application readiness tracking
* Networking research structure
* Manual review checkpoints
* HR analytics and people operations concepts

## Important Note

This project is shared as a portfolio project to demonstrate process design, HR analytics thinking, and workflow automation skills.

The public version is intentionally limited and sanitized. It is not intended to be used as a mass-application tool.
