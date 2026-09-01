# Nathan Parisot

InfoSec analyst, TS cleared. Vulnerability management, RMF and STIGs during the day.
Linux, self-hosting and automation the rest of the time.

Right now I'm working toward **RHCSA (EX200 v10)** in a lab I built and run myself, and
moving further into hardening and compliance automation — OpenSCAP, the SCAP Security
Guide, and Ansible-delivered STIG and CIS baselines.

## Projects

| Project | What it is |
|---|---|
| **[homelab](https://github.com/Paris0t/homelab)** | A single-node Proxmox server running household DNS, a password vault, monitoring, file sync and two RHEL study labs — plus write-ups of the faults I hit and how I worked out what was actually wrong. |
| **[JobSentry](https://github.com/Paris0t/JobSentry)** | Scrapes job boards, scores each listing against my profile with Claude, and emails a digest of the ones worth reading. Aimed at cleared roles, which most job tools skip. It's how I found my current job. |
| **[SOAR-EDR Lab](https://github.com/Paris0t/SOAR-EDR-Project)** | Incident response automation built on Tines and LimaCharlie, alerting into Slack, tested against generated attack telemetry. |
| **[Midas](https://github.com/Paris0t/midas-funding-bot)** | A funding-rate strategy on Hyperliquid perps, paper-traded for eight months across 766 closed trades. It found no detectable edge — profit factor 0.86, 95% CI [0.80, 1.56] — so I wrote that up rather than keep tuning until the backtest looked good. |

## A few things I've written up

- [The SSD wasn't dying — SATA power management was](https://github.com/Paris0t/homelab/blob/main/docs/sata-link-power-management.md) — 2,700 ATA errors a day and a silent throttle to a quarter speed, on a drive with a clean SMART report.
- [Four days of silent backups](https://github.com/Paris0t/homelab/blob/main/docs/silently-broken-backups.md) — one invalid line in `jobs.cfg` took down every backup job, and the only place it was reported was a unit journal.
- [Checking an orphaned ISO before deleting it](https://github.com/Paris0t/homelab/blob/main/docs/capacity-recovery.md) — recovering 72 GB, including the file that looked equally dead but was mounted on two running VMs.

## Elsewhere

[LinkedIn](https://linkedin.com/in/nathan-parisot) · [YouTube](https://www.youtube.com/@ItsCynik) · [Buy me a coffee](https://buymeacoffee.com/paris0t)
