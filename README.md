# Power Automate – Outlook Email Processing/Forwarding with Delay

## Overview
This repository contains a reference Power Automate flow that demonstrates
controlled, sequential processing of Outlook emails using Apply to each
and Delay.

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
- Unmanaged solution ZIP
- Sample screenshots
- Documentation

## Related Blog
A full walkthrough is available here:
[Power Automate: How to Process and Forward Emails with Delay (Step‑by‑Step Guide)](https://sunilpashikanti.blogspot.com/2026/04/power-automate-process-emails-with-delay-step-by-step.html)

## License
MIT
