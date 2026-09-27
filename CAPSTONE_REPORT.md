# Task 5 — Capstone Project & Incident Response

## Capstone Title
**Controlled-Lab Web Application Security Assessment and Incident Response Simulation**

## Objective
Combine reconnaissance, scanning, web testing, logging, mitigation, and incident response into one controlled project.

## Architecture
User Browser
     |
     v
DVWA Training Web App
     |
     +---- Apache/Web Logs
     |
     v
Log Collector / Mini-SIEM
     |
     v
Alert -> Triage -> Containment -> Eradication -> Recovery -> Lessons Learned

## Project phases
### 1. Planning
Define scope, objectives, tools, timeline, and authorization.

### 2. Assessment
Perform controlled reconnaissance and scanning against the lab application/network.

### 3. Web testing
Document selected vulnerabilities and their mitigations.

### 4. Detection
Collect sample web/security logs and identify suspicious patterns.

### 5. Incident response simulation
- Detect
- Triage
- Contain
- Eradicate
- Recover
- Produce post-incident report

### 6. Final documentation
Include executive summary, methodology, findings, mitigations, diagrams, screenshots, and tool outputs.

## Sample incident
Scenario: repeated suspicious web requests are observed against the training application.

Detection evidence:
- repeated requests from the same lab source
- unusual parameter patterns
- authentication failures

Response:
- validate the alert
- isolate/block the simulated source inside the lab
- preserve logs
- remove the simulated vulnerable condition
- retest
- document lessons learned

## Executive summary template
This project evaluated an intentionally vulnerable web application inside an isolated training environment. The assessment combined network discovery, application security testing, logging, and incident-response simulation. Findings were documented with evidence and paired with defensive mitigations. No external or unauthorized systems were tested.

## Final deliverables
- Capstone report PDF
- GitHub repository
- 12-minute final presentation video
