# Changelog

## 2026-04-22

- Bundled the M365 PNG logos (copilot, outlook, teams, word, excel, powerpoint, onedrive, m365) so app icons render on the deployed site — earlier deploy was index-only.
- Foundry screen repurpose finished: removed the audio waveform + red "Evaluating" recording indicator, retinted to Foundry magenta/purple, replaced with an eval-run progress bar that shows policy-ground-match progress.
- Aligned all four personas (Alex, Marcus, Maria, Dan) to show the same six canonical MSDCR custom agents on Home — role-specific pill text per persona, same agent set across.
- Added three new mock app-shells: Power Apps (case-management intake), Power Automate (grievance + PRR SLA timers, visitation exception routing, classification notifier), Power Pages (public family & visitor portal). Home grid + waffle tiles wired. Dataverse table callout added to Home.
- Enterprise polish pass on Power Apps and Power Pages: added MSDCR agency seal SVG, application stepper, signature chain-of-custody block, OFFICIAL USE watermark, authenticated-session widget, .gov-style secure banner, inline SVG connector logos, branded enterprise footer. No external dependencies.

## 2026-04-21

- Initial commit — MSDCR (Meridian State Department of Corrections and Rehabilitation) Microsoft 365 + Copilot demo.
- Transformed from the prior Meridian State University HR demo framework.
- Six custom Copilot Studio agents showcased: Policy Copilot, Visitation Front Door, Grievance & PRR Router, Reentry Program Match, Records Request Desk, Classification Packet Prep.
- Added the four-layer Microsoft AI stack callout on Home (M365 Copilot · Copilot Studio · Power Platform · Microsoft Foundry).
- Classification Packet Prep (UC6) carries a visible "Requires officer approval" pill and Foundry evaluation score; Dragon/DAX screen repurposed as a Microsoft Foundry governance & evaluations view.
- 24-week rollout roadmap aligned to UC1→UC6 complexity order, Foundry called out as the governance spine for UC6.
- Configured for Azure Static Web Apps deployment via GitHub Actions.
