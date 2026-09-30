# Changelog

Changes to the home lab and its documentation are recorded here. A documentation entry does not imply a service has been deployed.

## 2026-09-30

### Dell workstation assessments
- Expanded the T5810 report with seven captioned screenshots covering BIOS settings, PERC disk detection, and Ubuntu drive, partition, and read-only volume inspection.
- Added the T3600 no-display troubleshooting record, including memory isolation, graphics-card tests, and the pending direct display connection.
- Added the Precision Tower 5810 recovery and storage assessment: 64 GB RAM installation restored video; Ubuntu live USB inspection and SMART checks completed; OS installation and RAID creation remain pending.
- Added small, clickable chassis photos at the top of the T310, T3600, and Precision Tower 5810 reports.
- Linked the workstation reports from the README and hardware inventory.

## 2026-09-23

### Repository foundation
- Expanded the portfolio README with goals, current status, navigation, and a provisional roadmap.
- Added starter hardware, architecture, networking, virtualization, troubleshooting, project, configuration, and image sections.
- Added an initial hardware inventory and a `.gitignore` for local secrets and large machine images.

### Dell PowerEdge T310
- Documented boot recovery, RAID 10 rebuild, and initial disk and memory checks.
- Confirmed all four disks online and recorded BMC network reachability; web access on TCP ports 80 and 443 remained unavailable.
- Enabled IPMI over LAN; remote IPMI testing remains pending.
- Paused evaluation with a one-time revisit reminder for October 21, 2026.
