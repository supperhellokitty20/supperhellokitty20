<div align="center">

# Hi, I'm qtduck 👋

### System Administrator · Security Researcher · CTF Player

[![Published CVEs](https://img.shields.io/badge/Published_CVEs-5-7c3aed?style=for-the-badge)](#published-security-research)
[![Security Research](https://img.shields.io/badge/Focus-Security_Research-0ea5e9?style=for-the-badge)](#published-security-research)
[![CTF Team](https://img.shields.io/badge/CTF_Team-ResetSec-ef4444?style=for-the-badge)](https://ctftime.org/team/266022)

I build and operate systems, investigate security flaws, and enjoy turning curious observations into responsible disclosures.

[Website](https://master-rizz.lol) · [Security blog](http://blog.master-rizz.lol) · [HackerOne](https://hackerone.com/fizzi) · [GitHub](https://github.com/supperhellokitty20)

</div>

## 🛡️ Published Security Research

The following vulnerabilities were responsibly reported and publicly disclosed. GitHub Security Advisory entries credit
[`@supperhellokitty20`](https://github.com/supperhellokitty20) as a **reporter** where shown; other reports include vendor or HackerOne attribution.

| CVE | Project | Finding | Severity | Advisory / reference |
|:---|:---|:---|:---:|:---:|
| **CVE-2026-55420** | [Discourse](https://github.com/discourse/discourse) | Remote code execution via PDF uploads | **High** | [GHSA-7wq5-jgww-5rw3](https://github.com/discourse/discourse/security/advisories/GHSA-7wq5-jgww-5rw3) |
| **CVE-2026-39251** | [tmux](https://github.com/tmux/tmux) | Heap overflow in `sixel_print_add` affecting versions 3.4–3.6a | **Unrated** | [Fix commit](https://github.com/tmux/tmux/commit/95e40115a2cedbd1a0bd29fb58e4a66e5ab01ea1) |
| **CVE-2026-54301** | [n8n](https://github.com/n8n-io/n8n) | Same-Origin XSS in Respond to Webhook Node | **High** | [GHSA-v733-mwr6-fgcm](https://github.com/n8n-io/n8n/security/advisories/GHSA-v733-mwr6-fgcm) |
| **CVE-2026-50130** | [Pi-hole](https://github.com/pi-hole/pi-hole) | Local privilege escalation from `pihole` to root via logrotate | **High** | [GHSA-h8w9-qx2v-wrww](https://github.com/pi-hole/pi-hole/security/advisories/GHSA-h8w9-qx2v-wrww) |
| **CVE-2026-49246** | [Jellyfin](https://github.com/jellyfin/jellyfin) | Potential MKV attachment filename path traversal to RCE | **Low** | [GHSA-f47c-m7gr-q92j](https://github.com/jellyfin/jellyfin/security/advisories/GHSA-f47c-m7gr-q92j) |

> CVE-2026-55420 was reported to Discourse through HackerOne by [`fizzi`](https://hackerone.com/fizzi). The public GitHub advisory does not list reporter credits.

## 🔐 Responsible Disclosure

I follow coordinated disclosure practices and publish research details only after the affected project has released its advisory or fix.

<div align="center">

_Break things thoughtfully. Report them responsibly. Make software safer._

</div>
