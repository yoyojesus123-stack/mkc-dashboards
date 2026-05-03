# MKC Developmental Commission Dashboard

Google Apps Script web app for managing employees and projects.

## Features
- Dashboard with project status summary
- Employee management with ET number color coding
- Project tracking with auto-calculated status
- Region summary
- Reports

## Project Status Logic
| Condition | Status |
|-----------|--------|
| > 5 years from signing | Expired |
| ~5 years (4.5-5.5) | Terminal Report |
| ~2.5 years (2.0-2.5) | Mid Term |
| Below 5 years | On The Way |
| No signing date | Excluded |

## Setup
1. Open Google Sheets → Extensions → Apps Script
2. Copy Code.gs content
3. Create Dashboard.html file
4. Run setupDashboard()
5. Deploy as web app

## License
MIT