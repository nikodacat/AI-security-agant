# CVE Scan Report

_Generated 2026-04-29 19:00 UTC_

## Summary

- Host: `linux` (scanned at 2026-04-29T18:59:16+00:00)
- Inventory: **676** packages
- KEV catalog: **1585** entries (version 2026.04.28, released 2026-04-28T17:29:22.212Z)
- Findings: **9** (7 unique CVEs across 7 packages)
  - Vulnerable: **3**
  - Unknown (no NVD bounds or no installed version): **1**
  - Patched (version not in affected range): **5**
- Explanation backend: `fallback`

## Findings (vulnerable + unknown)

| Verdict | Severity | CVE | Package@version | KEV product | Match |
|---|---|---|---|---|---|
| 🔴 VULN | EXPLOITED | `CVE-2025-32463` | sudo @ `1.9.15p5-3ubuntu5.24.04.2` | Sudo / Sudo | vendor+product+product-only (98) |
| 🔴 VULN | EXPLOITED | `CVE-2025-48384` | git @ `1:2.43.0-1ubuntu7.3` | Git / Git | vendor+product+product-only (98) |
| 🔴 VULN | EXPLOITED | `CVE-2025-48384` | git-man @ `1:2.43.0-1ubuntu7.3` | Git / Git | alias+product-only (98) |
| 🟡 UNK | EXPLOITED | `CVE-2014-6278` | bash @ `5.2.21-2ubuntu4` | GNU / GNU Bash | alias+product-only (98) |

_5 patched finding(s) hidden. Re-run with `--show-patched` to include them._

## Detail

### 🔴 VULN  **[EXPLOITED]** `CVE-2025-32463` — Sudo Inclusion of Functionality from Untrusted Control Sphere Vulnerability

- Installed: `sudo` @ `1.9.15p5-3ubuntu5.24.04.2` (vendor `Ubuntu Developers <ubuntu-devel-discuss@lists.ubuntu.com>`)
- KEV vendor / product: Sudo / Sudo
- Date added to KEV: 2025-09-29
- CISA due date: 2025-10-20
- Match: `vendor+product+product-only` (score 98)
- Verdict: **vulnerable** — Installed 1.9.15p5-3ubuntu5.24.04.2 matches affected range >=1.9.14, <1.9.17
- CWEs: CWE-829

Sudo contains an inclusion of functionality from untrusted control sphere vulnerability. This vulnerability could allow local attacker to leverage sudo’s -R (--chroot) option to run arbitrary commands as root, even if they are not listed in the sudoers file. 建議動作：Apply mitigations per vendor instructions, follow applicable BOD 22-01 guidance for cloud services, or discontinue use of the product if mitigations are unavailable.。

### 🔴 VULN  **[EXPLOITED]** `CVE-2025-48384` — Git Link Following Vulnerability

- Installed: `git` @ `1:2.43.0-1ubuntu7.3` (vendor `Ubuntu Developers <ubuntu-devel-discuss@lists.ubuntu.com>`)
- KEV vendor / product: Git / Git
- Date added to KEV: 2025-08-25
- CISA due date: 2025-09-15
- Match: `vendor+product+product-only` (score 98)
- Verdict: **vulnerable** — Installed 1:2.43.0-1ubuntu7.3 matches affected range <2.43.7
- CWEs: CWE-59, CWE-436

Git contains a link following vulnerability that stems from Git’s inconsistent handling of carriage return characters in configuration files. 建議動作：Apply mitigations per vendor instructions, follow applicable BOD 22-01 guidance for cloud services, or discontinue use of the product if mitigations are unavailable.。

### 🔴 VULN  **[EXPLOITED]** `CVE-2025-48384` — Git Link Following Vulnerability

- Installed: `git-man` @ `1:2.43.0-1ubuntu7.3` (vendor `Ubuntu Developers <ubuntu-devel-discuss@lists.ubuntu.com>`)
- KEV vendor / product: Git / Git
- Date added to KEV: 2025-08-25
- CISA due date: 2025-09-15
- Match: `alias+product-only` (score 98)
- Verdict: **vulnerable** — Installed 1:2.43.0-1ubuntu7.3 matches affected range <2.43.7
- CWEs: CWE-59, CWE-436

Git contains a link following vulnerability that stems from Git’s inconsistent handling of carriage return characters in configuration files. 建議動作：Apply mitigations per vendor instructions, follow applicable BOD 22-01 guidance for cloud services, or discontinue use of the product if mitigations are unavailable.。

### 🟡 UNK  **[EXPLOITED]** `CVE-2014-6278` — GNU Bash OS Command Injection Vulnerability

- Installed: `bash` @ `5.2.21-2ubuntu4` (vendor `Ubuntu Developers <ubuntu-devel-discuss@lists.ubuntu.com>`)
- KEV vendor / product: GNU / GNU Bash
- Date added to KEV: 2025-10-02
- CISA due date: 2025-10-23
- Match: `alias+product-only` (score 98)
- Verdict: **unknown** — NVD lookup failed: The read operation timed out
- CWEs: CWE-78

GNU Bash contains an OS command injection vulnerability which allows remote attackers to execute arbitrary commands via a crafted environment. 建議動作：Apply mitigations per vendor instructions, follow applicable BOD 22-01 guidance for cloud services, or discontinue use of the product if mitigations are unavailable.。

## How to read this report

Each finding maps to a vulnerability that **CISA has confirmed is being exploited in the wild** (KEV). Verdicts are derived from NVD affected-version ranges:

- **Vulnerable**: your installed version is inside an affected range. Patch ASAP.
- **Unknown**: NVD has no bounded range for this CVE, or your inventory has no version. Treat as needs-review.
- **Patched**: your installed version is outside every affected range. Informational.

Run with `--check-versions` to populate verdicts (otherwise everything is `unknown`). Add `--show-patched` if you want the detail blocks for patched items as well.
