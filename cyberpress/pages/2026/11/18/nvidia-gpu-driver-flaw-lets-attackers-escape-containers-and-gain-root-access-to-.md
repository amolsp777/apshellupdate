---
title: "NVIDIA GPU Driver Flaw Lets Attackers Escape Containers and Gain Root Access to Linux Hosts"
source: "CyberPress"
source_url: "https://cyberpress.org/nvidia-gpu-driver-flaw/"
published_at: "2026-11-18T10:59:33.000Z"
published_at_central: "Nov 18, 2026, 4:59:33 AM"
created_at: "2026-11-18T11:00:14.147Z"
created_at_central: "Nov 18, 2026, 5:00:14 AM"
timezone: "America/Chicago"
tags:
  - cyber
  - vulnerability
---
An out-of-bounds write in NVIDIA’s Linux GPU kernel driver lets an unprivileged process escape a GPU-enabled container and gain root access on the host. The flaw, dubbed ForgePtr and tracked as CVE-2026-47501, requires local access to an affected GPU device but does not require CAP_SYS_ADMIN, special group membership, or a privileged container. On shared AI 
[Read the full post](https://cyberpress.org/nvidia-gpu-driver-flaw/)
Processed: Nov 18, 2026, 5:00:14 AM (Central)