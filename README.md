# Power Automate – Outlook Email Processing/Forwarding with Delay

## Overview
This repository contains a reference Power Automate flow that demonstrates
controlled, sequential processing of Outlook emails using Apply to each
and Delay.

![Microsoft Community](https://img.shields.io/badge/Microsoft%20Community-Super%20User-orange?style=for-the-badge&logo=microsoft)
![License](https://img.shields.io/badge/License-MIT-yellow?style=for-the-badge)
![Power Platform](https://img.shields.io/badge/Platform-Power%20Platform-blue?style=for-the-badge&logo=power-platform)
![Power Automate](https://img.shields.io/badge/Platform-Power%20Automate-orange?style=for-the-badge&logo=power-platform)

The flow was built, tested, and validated in a personal Microsoft 365 tenant
and is shared for community learning.

## Features
- Processes emails from a selected folder
- Sends emails sequentially
- Enforces delay between sends
- Prevents reprocessing via Move email
- Explicit concurrency control (degree = 1)

## Why this exists
Delay actions may appear to work without concurrency control for small datasets.
This solution demonstrates the **guaranteed** pattern suitable for reuse.

## Included

- **Unmanaged solution ZIP**  
  A reusable Power Automate solution containing the sample email‑processing flow. Available from the GitHub Releases section.

- **Sample screenshots**  
  Flow design and execution history screenshots captured from a real run, including delay timing.

- **Documentation**  
  A complete step-by-step walkthrough with configuration details and screenshots is available here:
[Power Automate: How to Process and Forward Emails with Delay (Step‑by‑Step Guide)](https://sunilpashikanti.blogspot.com/2026/04/power-automate-process-emails-with-delay-step-by-step.html)

In this sample, emails are moved after processing. In production scenarios, you may further guard this with conditional run-after settings.

## Download

[![Download ZIP](https://img.shields.io/badge/Download-Solution-blue?style=for-the-badge&logo=github)](https://github.com/spashikanti/power-automate-forward-email-delay-pattern/releases/latest)
[![Release](https://img.shields.io/github/v/release/spashikanti/power-automate-forward-email-delay-pattern?style=for-the-badge&logo=github&color=brightgreen)](https://github.com/spashikanti/power-automate-forward-email-delay-pattern/releases/latest)
[![Total Downloads](https://img.shields.io/github/downloads/spashikanti/power-automate-forward-email-delay-pattern/total?style=for-the-badge&color=yellow)](https://github.com/spashikanti/power-automate-forward-email-delay-pattern/releases)

The latest release (unmanaged solution ZIP) is available here:  
👉 https://github.com/spashikanti/power-automate-forward-email-delay-pattern/releases/latest


## Screenshots

### Flow Overview
![Flow overview](screenshots/flow-overview.png)

### Run History (Delay respected)
![Run history](screenshots/run-history-delay.png)


## License
MIT
