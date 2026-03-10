# Release Governance Lite – ServiceNow

A scoped ServiceNow application that demonstrates ITIL-aligned release management and deployment governance using Catalog, Change, Flow Designer, approvals, and checklist tasks.

## Project Objective
To automate release intake, enforce governance controls, generate the correct change path by environment, and track deployment readiness through release checklist tasks.

## Features Implemented
- Release record lifecycle
- Release Deployment Request catalog item
- Environment-based change creation
- Prod releases require stronger approval controls
- Release checklist tasks for testing, communications, backout, and deployment
- High-risk governance rule requiring backout plan
- Automated release and change closure

## Technologies Used
- ServiceNow Studio
- Flow Designer
- Service Catalog
- Change Management
- Business Rules
- Scoped application design

## Demo Scenarios
1. Prod high-risk release → normal change + approvals + checklist tasks
2. QA release → lighter change path
3. High-risk release without backout plan → blocked

## Notes
This project demonstrates release governance patterns commonly used in enterprise ITIL environments.
