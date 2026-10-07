# Clinical Summary Demo

A SMART on FHIR proof of concept for care management. When a care manager
opens a member's chart, the app reads that member's clinical data through
FHIR and displays a consolidated summary, with a source citation on each
item, to help prepare for outreach calls.

## What it does
- Launches from within the EHR with the patient in context (SMART EHR launch)
- Reads patient demographics, problems, labs and vitals, medications,
  encounters, clinical notes, and coverage (read-only)
- Presents a summary for the care manager to review; a clinician makes all decisions

## Data
- This is a sandbox proof of concept using synthetic test data only
- No real patient data is used or stored
- Read-only; the app makes no changes to the record

## Status
Non-production. Not for clinical use.
