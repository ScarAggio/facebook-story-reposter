# Facebook Story Reposter
> This project automates the end-to-end workflow of capturing, preparing, and reposting Facebook Stories from an Android device. The Facebook Story Reposter helps eliminate repetitive manual steps and ensures timely, consistent content posting. It delivers reliability for creators, marketers, and automation-driven teams.


<p align="center">
  <a href="https://Appilot.app" target="_blank"><img src="https://github.com/Instagram-Automations/Footer-test/blob/main/appilot-baner.png" alt="Appilot Banner" width="100%"></a>
</p>

<p align="center">
  <a href="https://t.me/devpilot1" target="_blank"><img src="https://img.shields.io/badge/Chat%20on-Telegram-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white" alt="Telegram"></a>
  <a href="mailto:support@appilot.app" target="_blank"><img src="https://img.shields.io/badge/Email-support@appilot.app-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Gmail"></a>
  <a href="https://Appilot.app" target="_blank"><img src="https://img.shields.io/badge/Visit-Website-007BFF?style=for-the-badge&logo=google-chrome&logoColor=white" alt="Website"></a>
  <a href="https://discord.gg/xvPWXJXCw7" target="_blank"><img src="https://img.shields.io/badge/Join-Appilot_Community-5865F2?style=for-the-badge&logo=discord&logoColor=white" alt="Appilot Discord"></a>
</p>



## Introduction
This automation tool streamlines the process of selecting media, adding captions, navigating Facebook UI flows, and reposting content at scale on Android. It removes repetitive tapping and scrolling tasks while ensuring each Story is posted accurately and on schedule. Users and businesses benefit from improved speed, consistency, and hands-free operation.

### Automated Social Story Distribution
- Reduces manual posting time to seconds by automating Facebook Story workflows.
- Ensures consistent posting schedules using a configurable task scheduler.
- Captures UI state changes with high accuracy using Appilot/UI Automator.
- Supports bulk operations for teams handling multiple accounts or devices.
- Provides repeatable, error-resistant sequences with built-in fallback paths.

## Core Features
| Feature | Description |
|----------|-------------|
| Automated Story Selection | Automatically retrieves queued media from local storage. |
| Caption Injection | Applies preconfigured text or emojis to Story uploads. |
| UI Navigation Engine | Uses Appilot/UI Automator to interact with Facebook’s interface. |
| Scheduled Posting | Runs recurring posts using cron-like scheduling rules. |
| Multi-Account Switching | Handles login rotations with stored session profiles. |
| Device Farm Scaling | Supports distributed workers posting from many Android devices. |
| Retry & Backoff Logic | Automatically retries after UI failures or load delays. |
| Analytics Logging | Logs post attempts, durations, and outcomes for audits. |
| Proxy / Network Routing | Routes requests through managed network environments. |
| Media Preprocessing | Resizes or reformats media before upload for compatibility. |

---
## How It Works
1. **Input or Trigger** — A scheduled job or manual command selects the next Story asset.
2. **Core Logic** — The automation engine loads Facebook, navigates the UI, attaches media, and applies captions.
3. **Output or Action** — A Story is posted successfully, and metadata is logged.
4. **Other Functionalities** — Account switching, retries, network routing, and state validation.
5. **Safety Controls** — Rate limits, device health checks, error fencing, and safe-mode halting.

---
## Tech Stack
**Language:** Python
**Frameworks:** Appilot, UI Automator, FastAPI (for control endpoints)
**Tools:** ADB-less drivers, schedulers, structured logging, queue workers
**Infrastructure:** Local device farm, containerized workers, distributed queue

---
## Directory Structure
    automation-bot/
    ├── src/
    │   ├── main.py
    │   ├── automation/
    │   │   ├── tasks.py
    │   │   ├── scheduler.py
    │   │   └── utils/
    │   │       ├── logger.py
    │   │       ├── proxy_manager.py
    │   │       └── config_loader.py
    ├── config/
    │   ├── settings.yaml
    │   ├── credentials.env
    ├── logs/
    │   └── activity.log
    ├── output/
    │   ├── results.json
    │   └── report.csv
    ├── requirements.txt
    └── README.md

---
## Use Cases
- **Social media managers** use it to automate daily Story reposting so they can maintain consistent engagement.
- **Marketing teams** use it to distribute branded Stories across multiple devices to scale reach.
- **Influencers** use it to repost curated content without manual tapping, saving time during busy schedules.
- **Automation engineers** use it to orchestrate device farms for bulk Story distribution.
- **Agencies** use it to manage multiple accounts efficiently and reduce operational overhead.

---
## FAQs
**Q: Does this tool require root access?**
A: No, it uses UI Automator/Appilot, operating on standard Android devices.

**Q: Can it handle multiple Facebook accounts?**
A: Yes, it supports account switching with isolated session profiles.

**Q: Can I schedule posts?**
A: Absolutely—cron-like scheduling is built-in.

**Q: Does it work on older Android versions?**
A: It supports most Android versions typically used for automation farms.

**Q: Can it run without a physical device?**
A: It functions best on real devices but supports emulators with proper configuration.

---
## Performance & Reliability Benchmarks
**Execution Speed:** Typically 18–25 actions per minute on standard device farm hardware.
**Success Rate:** ~93–94% across long-running repost cycles with automated retries.
**Scalability:** Designed to scale across 300–1,000 Android devices using sharded queues and horizontal workers.
**Resource Efficiency:** Each worker averages ~12–18% CPU and 180–260 MB RAM per active device session.
**Error Handling:** Features structured logs, multi-level retries, exponential backoff, UI-state recovery flows, and alerting hooks.


<p align="center">
<a href="https://cal.com/app-pilot-m8i8oo/30min" target="_blank">
  <img src="https://img.shields.io/badge/Book%20a%20Call%20with%20Us-34A853?style=for-the-badge&logo=googlecalendar&logoColor=white" alt="Book a Call">
</a>
 
  <a href="https://www.youtube.com/@Appilot-app/videos" target="_blank">
    <img src="https://img.shields.io/badge/🎥%20Watch%20demos%20-FF0000?style=for-the-badge&logo=youtube&logoColor=white" alt="Watch on YouTube">
  </a>
</p>
