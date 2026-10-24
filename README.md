# Status Page

![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?logo=react&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-6B1EB9?logo=vite&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/TailwindCSS-38BDF8?logo=tailwindcss&logoColor=white)
![Cloudflare](https://img.shields.io/badge/Cloudflare-F38020?logo=cloudflare&logoColor=white)
![Make](https://img.shields.io/badge/Make-6D00CD?logo=make&logoColor=white)
![ntfy](https://img.shields.io/badge/ntfy-50B7A1?logo=ntfy&logoColor=white)

Status page for my projects built on Cloudflare.

## Overview

Fork of UptimeWorker with custom modifications. It monitors my projects (Portfolio, Set Intersection, Table Tennis Manager) and splits TTM into FE/BE/DB for granular monitoring. The granular split was a bit of a pain to set up, but now I can see exactly which part is failing. And for notifications I use Make as a bridge between Cloudflare Workers and ntfy, since they can't talk to each other directly.

## Tech stack

- **Core:** TypeScript, React, Vite, TailwindCSS
- **Deploy:** Cloudflare Pages, Cloudflare Workers
- **Storage:** Cloudflare KV
- **Automation:** Make
- **Notifications:** ntfy

## Website

[Status Page](https://mk-forge-status.pages.dev)

## Screenshots

![Status page](https://raw.githubusercontent.com/mk-forge/status-page/main/Screenshots/status_page.png)
![Status page detail](https://raw.githubusercontent.com/mk-forge/status-page/main/Screenshots/status_page_detail.png)
![Make automation](https://raw.githubusercontent.com/mk-forge/status-page/main/Screenshots/make_automation.png)
![Ntfy notification](https://raw.githubusercontent.com/mk-forge/status-page/main/Screenshots/ntfy_notification.png)

## Credits

Based on [UptimeWorker](https://github.com/UptimeWorker/UptimeWorker) by [slymb](https://github.com/slymb).

## License

[Apache-2.0](LICENSE)