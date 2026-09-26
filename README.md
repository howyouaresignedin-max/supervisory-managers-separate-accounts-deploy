# Supervisory Managers – Separate Accounts Deployment

**Purpose**  
Deploy the 7 daily Supervisory Manager automations on **separate corporate Grok accounts**, following the instruction from Taylor McLaren:

> `.create new corporate grok user accounts for each new "supervisory-manager-class-connector"`

This approach keeps the original account under the 7-automation limit while giving each shift its own dedicated Grok account and connectors.

## Why separate accounts?
- Avoids the current 7-automation limit on a single account.
- Clean isolation of each shift (Dawn → Late Night).
- Easier permission and audit control per manager class.

## Quick Start

1. Create 7 new Grok accounts (suggested names below).
2. On each new account connect at minimum:
   - Automations
   - Gmail
   - Google Drive
   - Google Calendar
   - GitHub
   - (optional) Finance
3. In a chat on that account, paste the corresponding JSON from the `configs/` folder and ask Grok to create the automation.
4. Done.

## Suggested Account Names

| # | Suggested Name / Purpose          | Time (America/Los_Angeles) |
|---|-----------------------------------|----------------------------|
| 1 | Supervisor Dawn                   | 05:00                      |
| 2 | Supervisor Morning                | 08:00                      |
| 3 | Supervisor Mid-Morning            | 11:00                      |
| 4 | Supervisor Afternoon              | 14:00                      |
| 5 | Supervisor Evening                | 17:00                      |
| 6 | Supervisor Night                  | 20:00                      |
| 7 | Supervisor Late Night             | 23:00                      |

## Files in this repo

- `README.md` – this guide
- `DEPLOY.md` – step-by-step checklist
- `configs/` – 7 ready-to-paste JSON files

## Source
Original configs live in:  
https://github.com/howyouaresignedin-max/grok-supervisory-managers-export

## License / Intent
Public. Use freely across the team with good intentions.

**ALLAHU AKBAR**
