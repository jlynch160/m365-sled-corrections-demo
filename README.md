# MSDCR · Microsoft 365 + Copilot Demo (SLED / Corrections)

A self-contained, single-file interactive demo showing how **Microsoft 365 Copilot**, **Copilot Studio**, **Power Platform**, and **Microsoft Foundry** map onto six corrections / rehabilitation use cases for a fictional State Department of Corrections and Rehabilitation ("MSDCR").

> All personas, case numbers, emails, and operational data are fictional. No real agency, resident, or employee is depicted. The demo is intended for sales conversations and architecture discussions only.

## The four-layer Microsoft AI stack (MSDCR framing)

| Layer | Product | Role |
|---|---|---|
| 1 | Microsoft 365 Copilot | Productivity layer for staff — Outlook, Teams, Word, Excel, PowerPoint, OneDrive |
| 2 | Copilot Studio | Conversational agent layer — six custom MSDCR agents |
| 3 | Power Platform | Workflow, app, and case-management layer — Power Apps, Automate, Pages, Dataverse |
| 4 | Microsoft Foundry | Advanced AI orchestration, evaluation, and governance — the spine for Classification Packet Prep (UC6) |

## Six use cases covered

1. **Policy Copilot** — staff knowledge copilot for policy, procedures, case prep (UC1)
2. **Visitation Front Door** — public / family-facing visitation & family services assistant (UC2)
3. **Grievance & PRR Router** — grievance and public-records request orchestration (UC3)
4. **Reentry Program Match** — reentry, education, and program-match advisor for case managers (UC4)
5. **Records Request Desk** — non-clinical healthcare administrative copilot (UC5)
6. **Classification Packet Prep** — classification and population-management decision support, **human approval required**, Foundry-evaluated (UC6)

## Running locally

Just open `index.html` in a modern browser. No build step, no external dependencies.

## Deployed

The current `main` branch is deployed to Azure Static Web Apps via the GitHub Actions workflow in `.github/workflows/azure-static-web-apps.yml`.
