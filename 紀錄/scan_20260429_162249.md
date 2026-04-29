# CVE Scan Report

_Generated 2026-04-29 16:22 UTC_

## Summary

- Host: `linux` (scanned at 2026-04-29T16:22:49+00:00)
- Inventory: **676** packages
- KEV catalog: **1585** entries (version 2026.04.28, released 2026-04-28T17:29:22.212Z)
- Findings: **47** (21 unique CVEs across 36 packages)
- Ransomware-linked CVEs hit: **8** — treat as P0
- Explanation backend: `fallback`

## Findings

| Severity | CVE | Package | Vendor → KEV match | Match |
|---|---|---|---|---|
| RANSOMWARE | `CVE-2016-0151` | time | Microsoft / Client-Server Run-time Subsystem (CSRSS) | vendor+product+fuzzy (100) |
| RANSOMWARE | `CVE-2018-7602` | apport-core-dump-handler | Drupal / Core | vendor+product+fuzzy (100) |
| RANSOMWARE | `CVE-2018-7602` | at-spi2-core | Drupal / Core | vendor+product+fuzzy (100) |
| RANSOMWARE | `CVE-2018-7602` | fonts-dejavu-core | Drupal / Core | vendor+product+fuzzy (100) |
| RANSOMWARE | `CVE-2018-7602` | libevent-core-2.1-7t64 | Drupal / Core | vendor+product+fuzzy (100) |
| RANSOMWARE | `CVE-2018-7602` | libmaven3-core-java | Drupal / Core | vendor+product+fuzzy (100) |
| RANSOMWARE | `CVE-2018-7602` | ubuntu-release-upgrader-core | Drupal / Core | vendor+product+fuzzy (100) |
| RANSOMWARE | `CVE-2018-7602` | update-manager-core | Drupal / Core | vendor+product+fuzzy (100) |
| EXPLOITED | `CVE-2012-1889` | xml-core | Microsoft / XML Core Services | vendor+product+fuzzy (100) |
| EXPLOITED | `CVE-2014-0160` | openssl | OpenSSL / OpenSSL | vendor+product+fuzzy (100) |
| EXPLOITED | `CVE-2014-0160` | python3-openssl | OpenSSL / OpenSSL | vendor+product+fuzzy (100) |
| EXPLOITED | `CVE-2014-6278` | bash | GNU / GNU Bash | vendor+product+fuzzy (100) |
| EXPLOITED | `CVE-2017-0022` | xml-core | Microsoft / XML Core Services | vendor+product+fuzzy (100) |
| EXPLOITED | `CVE-2019-18988` | gsettings-desktop-schemas | TeamViewer / Desktop | vendor+product+fuzzy (100) |
| EXPLOITED | `CVE-2019-6340` | apport-core-dump-handler | Drupal / Core | vendor+product+fuzzy (100) |
| EXPLOITED | `CVE-2019-6340` | at-spi2-core | Drupal / Core | vendor+product+fuzzy (100) |
| EXPLOITED | `CVE-2019-6340` | fonts-dejavu-core | Drupal / Core | vendor+product+fuzzy (100) |
| EXPLOITED | `CVE-2019-6340` | libevent-core-2.1-7t64 | Drupal / Core | vendor+product+fuzzy (100) |
| EXPLOITED | `CVE-2019-6340` | libmaven3-core-java | Drupal / Core | vendor+product+fuzzy (100) |
| EXPLOITED | `CVE-2019-6340` | ubuntu-release-upgrader-core | Drupal / Core | vendor+product+fuzzy (100) |
| EXPLOITED | `CVE-2019-6340` | update-manager-core | Drupal / Core | vendor+product+fuzzy (100) |
| EXPLOITED | `CVE-2020-11023` | libjs-jquery | JQuery / JQuery | vendor+product+fuzzy (100) |
| EXPLOITED | `CVE-2020-28949` | tar | PEAR / Archive_Tar | vendor+product+fuzzy (100) |
| EXPLOITED | `CVE-2020-36193` | tar | PEAR / Archive_Tar | vendor+product+fuzzy (100) |
| EXPLOITED | `CVE-2021-3156` | sudo | Sudo / Sudo | vendor+product+fuzzy (100) |
| EXPLOITED | `CVE-2023-20867` | libpng-tools | VMware / Tools | vendor+product+fuzzy (100) |
| EXPLOITED | `CVE-2023-20867` | linux-tools-6.8.0-110 | VMware / Tools | vendor+product+fuzzy (100) |
| EXPLOITED | `CVE-2023-20867` | linux-tools-6.8.0-110-generic | VMware / Tools | vendor+product+fuzzy (100) |
| EXPLOITED | `CVE-2023-20867` | linux-tools-common | VMware / Tools | vendor+product+fuzzy (100) |
| EXPLOITED | `CVE-2023-20867` | linux-tools-generic | VMware / Tools | vendor+product+fuzzy (100) |
| EXPLOITED | `CVE-2023-20867` | packagekit-tools | VMware / Tools | vendor+product+fuzzy (100) |
| EXPLOITED | `CVE-2023-20867` | squashfs-tools | VMware / Tools | vendor+product+fuzzy (100) |
| EXPLOITED | `CVE-2024-23692` | file | Rejetto / HTTP File Server | vendor+product+fuzzy (100) |
| EXPLOITED | `CVE-2025-11953` | libcommons-cli-java | React Native Community / CLI | vendor+product+fuzzy (100) |
| EXPLOITED | `CVE-2025-32463` | sudo | Sudo / Sudo | vendor+product+fuzzy (100) |
| EXPLOITED | `CVE-2025-48384` | git | Git / Git | vendor+product+fuzzy (100) |
| EXPLOITED | `CVE-2025-48384` | git-man | Git / Git | vendor+product+fuzzy (100) |
| EXPLOITED | `CVE-2025-48543` | libpam-runtime | Android / Runtime | vendor+product+fuzzy (100) |
| EXPLOITED | `CVE-2025-48543` | uuid-runtime | Android / Runtime | vendor+product+fuzzy (100) |
| EXPLOITED | `CVE-2025-48543` | vim-runtime | Android / Runtime | vendor+product+fuzzy (100) |
| EXPLOITED | `CVE-2026-3502` | gpg-wks-client | TrueConf / Client | vendor+product+fuzzy (100) |
| EXPLOITED | `CVE-2026-3502` | landscape-client | TrueConf / Client | vendor+product+fuzzy (100) |
| EXPLOITED | `CVE-2026-3502` | openssh-client | TrueConf / Client | vendor+product+fuzzy (100) |
| EXPLOITED | `CVE-2026-3502` | ubuntu-pro-client | TrueConf / Client | vendor+product+fuzzy (100) |
| EXPLOITED | `CVE-2026-3502` | ubuntu-pro-client-l10n | TrueConf / Client | vendor+product+fuzzy (100) |
| EXPLOITED | `CVE-2021-3560` | polkitd | Red Hat / Polkit | vendor+product+fuzzy (92) |
| EXPLOITED | `CVE-2021-4034` | polkitd | Red Hat / Polkit | vendor+product+fuzzy (92) |

## Detail

### **[RANSOMWARE]** `CVE-2016-0151` — Microsoft Windows CSRSS Security Feature Bypass Vulnerability

- Installed: `time` (version `1.9-0.2build1`, vendor `Ubuntu Developers <ubuntu-devel-discuss@lists.ubuntu.com>`)
- KEV vendor / product: Microsoft / Client-Server Run-time Subsystem (CSRSS)
- Date added to KEV: 2022-03-28
- CISA due date: 2022-04-18
- Match: `vendor+product+fuzzy` (score 100)
- CWEs: CWE-264

The Client-Server Run-time Subsystem (CSRSS) in Microsoft mismanages process tokens, which allows local users to gain privileges via a crafted application. 建議動作：Apply updates per vendor instructions.。（已被勒索軟體用於實際攻擊）

### **[RANSOMWARE]** `CVE-2018-7602` — Drupal Core Remote Code Execution Vulnerability

- Installed: `apport-core-dump-handler` (version `2.28.1-0ubuntu3.8`, vendor `Ubuntu Developers <ubuntu-devel-discuss@lists.ubuntu.com>`)
- KEV vendor / product: Drupal / Core
- Date added to KEV: 2022-04-13
- CISA due date: 2022-05-04
- Match: `vendor+product+fuzzy` (score 100)

A remote code execution vulnerability exists within multiple subsystems of Drupal that can allow attackers to exploit multiple attack vectors on a Drupal site. 建議動作：Apply updates per vendor instructions.。（已被勒索軟體用於實際攻擊）

### **[RANSOMWARE]** `CVE-2018-7602` — Drupal Core Remote Code Execution Vulnerability

- Installed: `at-spi2-core` (version `2.52.0-1build1`, vendor `Ubuntu Developers <ubuntu-devel-discuss@lists.ubuntu.com>`)
- KEV vendor / product: Drupal / Core
- Date added to KEV: 2022-04-13
- CISA due date: 2022-05-04
- Match: `vendor+product+fuzzy` (score 100)

A remote code execution vulnerability exists within multiple subsystems of Drupal that can allow attackers to exploit multiple attack vectors on a Drupal site. 建議動作：Apply updates per vendor instructions.。（已被勒索軟體用於實際攻擊）

### **[RANSOMWARE]** `CVE-2018-7602` — Drupal Core Remote Code Execution Vulnerability

- Installed: `fonts-dejavu-core` (version `2.37-8`, vendor `Ubuntu Developers <ubuntu-devel-discuss@lists.ubuntu.com>`)
- KEV vendor / product: Drupal / Core
- Date added to KEV: 2022-04-13
- CISA due date: 2022-05-04
- Match: `vendor+product+fuzzy` (score 100)

A remote code execution vulnerability exists within multiple subsystems of Drupal that can allow attackers to exploit multiple attack vectors on a Drupal site. 建議動作：Apply updates per vendor instructions.。（已被勒索軟體用於實際攻擊）

### **[RANSOMWARE]** `CVE-2018-7602` — Drupal Core Remote Code Execution Vulnerability

- Installed: `libevent-core-2.1-7t64` (version `2.1.12-stable-9ubuntu2`, vendor `Ubuntu Developers <ubuntu-devel-discuss@lists.ubuntu.com>`)
- KEV vendor / product: Drupal / Core
- Date added to KEV: 2022-04-13
- CISA due date: 2022-05-04
- Match: `vendor+product+fuzzy` (score 100)

A remote code execution vulnerability exists within multiple subsystems of Drupal that can allow attackers to exploit multiple attack vectors on a Drupal site. 建議動作：Apply updates per vendor instructions.。（已被勒索軟體用於實際攻擊）

### **[RANSOMWARE]** `CVE-2018-7602` — Drupal Core Remote Code Execution Vulnerability

- Installed: `libmaven3-core-java` (version `3.8.7-2`, vendor `Ubuntu Developers <ubuntu-devel-discuss@lists.ubuntu.com>`)
- KEV vendor / product: Drupal / Core
- Date added to KEV: 2022-04-13
- CISA due date: 2022-05-04
- Match: `vendor+product+fuzzy` (score 100)

A remote code execution vulnerability exists within multiple subsystems of Drupal that can allow attackers to exploit multiple attack vectors on a Drupal site. 建議動作：Apply updates per vendor instructions.。（已被勒索軟體用於實際攻擊）

### **[RANSOMWARE]** `CVE-2018-7602` — Drupal Core Remote Code Execution Vulnerability

- Installed: `ubuntu-release-upgrader-core` (version `1:24.04.28`, vendor `Ubuntu Developers <ubuntu-devel-discuss@lists.ubuntu.com>`)
- KEV vendor / product: Drupal / Core
- Date added to KEV: 2022-04-13
- CISA due date: 2022-05-04
- Match: `vendor+product+fuzzy` (score 100)

A remote code execution vulnerability exists within multiple subsystems of Drupal that can allow attackers to exploit multiple attack vectors on a Drupal site. 建議動作：Apply updates per vendor instructions.。（已被勒索軟體用於實際攻擊）

### **[RANSOMWARE]** `CVE-2018-7602` — Drupal Core Remote Code Execution Vulnerability

- Installed: `update-manager-core` (version `1:24.04.12`, vendor `Ubuntu Developers <ubuntu-devel-discuss@lists.ubuntu.com>`)
- KEV vendor / product: Drupal / Core
- Date added to KEV: 2022-04-13
- CISA due date: 2022-05-04
- Match: `vendor+product+fuzzy` (score 100)

A remote code execution vulnerability exists within multiple subsystems of Drupal that can allow attackers to exploit multiple attack vectors on a Drupal site. 建議動作：Apply updates per vendor instructions.。（已被勒索軟體用於實際攻擊）

### **[EXPLOITED]** `CVE-2012-1889` — Microsoft XML Core Services Memory Corruption Vulnerability

- Installed: `xml-core` (version `0.19`, vendor `Ubuntu Developers <ubuntu-devel-discuss@lists.ubuntu.com>`)
- KEV vendor / product: Microsoft / XML Core Services
- Date added to KEV: 2022-06-08
- CISA due date: 2022-06-22
- Match: `vendor+product+fuzzy` (score 100)
- CWEs: CWE-119

Microsoft XML Core Services contains a memory corruption vulnerability which could allow for remote code execution. 建議動作：Apply updates per vendor instructions.。

### **[EXPLOITED]** `CVE-2014-0160` — OpenSSL Information Disclosure Vulnerability

- Installed: `openssl` (version `3.0.13-0ubuntu3.9`, vendor `Ubuntu Developers <ubuntu-devel-discuss@lists.ubuntu.com>`)
- KEV vendor / product: OpenSSL / OpenSSL
- Date added to KEV: 2022-05-04
- CISA due date: 2022-05-25
- Match: `vendor+product+fuzzy` (score 100)
- CWEs: CWE-125

The TLS and DTLS implementations in OpenSSL do not properly handle Heartbeat Extension packets, which allows remote attackers to obtain sensitive information. 建議動作：Apply updates per vendor instructions.。

### **[EXPLOITED]** `CVE-2014-0160` — OpenSSL Information Disclosure Vulnerability

- Installed: `python3-openssl` (version `23.2.0-1ubuntu0.1`, vendor `Ubuntu Developers <ubuntu-devel-discuss@lists.ubuntu.com>`)
- KEV vendor / product: OpenSSL / OpenSSL
- Date added to KEV: 2022-05-04
- CISA due date: 2022-05-25
- Match: `vendor+product+fuzzy` (score 100)
- CWEs: CWE-125

The TLS and DTLS implementations in OpenSSL do not properly handle Heartbeat Extension packets, which allows remote attackers to obtain sensitive information. 建議動作：Apply updates per vendor instructions.。

### **[EXPLOITED]** `CVE-2014-6278` — GNU Bash OS Command Injection Vulnerability

- Installed: `bash` (version `5.2.21-2ubuntu4`, vendor `Ubuntu Developers <ubuntu-devel-discuss@lists.ubuntu.com>`)
- KEV vendor / product: GNU / GNU Bash
- Date added to KEV: 2025-10-02
- CISA due date: 2025-10-23
- Match: `vendor+product+fuzzy` (score 100)
- CWEs: CWE-78

GNU Bash contains an OS command injection vulnerability which allows remote attackers to execute arbitrary commands via a crafted environment. 建議動作：Apply mitigations per vendor instructions, follow applicable BOD 22-01 guidance for cloud services, or discontinue use of the product if mitigations are unavailable.。

### **[EXPLOITED]** `CVE-2017-0022` — Microsoft XML Core Services Information Disclosure Vulnerability

- Installed: `xml-core` (version `0.19`, vendor `Ubuntu Developers <ubuntu-devel-discuss@lists.ubuntu.com>`)
- KEV vendor / product: Microsoft / XML Core Services
- Date added to KEV: 2022-05-24
- CISA due date: 2022-06-14
- Match: `vendor+product+fuzzy` (score 100)
- CWEs: CWE-200

Microsoft XML Core Services (MSXML) improperly handles objects in memory, allowing attackers to test for files on disk via a crafted web site. 建議動作：Apply updates per vendor instructions.。

### **[EXPLOITED]** `CVE-2019-18988` — TeamViewer Desktop Bypass Remote Login Vulnerability

- Installed: `gsettings-desktop-schemas` (version `46.1-0ubuntu1`, vendor `Ubuntu Developers <ubuntu-devel-discuss@lists.ubuntu.com>`)
- KEV vendor / product: TeamViewer / Desktop
- Date added to KEV: 2021-11-03
- CISA due date: 2022-05-03
- Match: `vendor+product+fuzzy` (score 100)
- CWEs: CWE-521

TeamViewer Desktop allows for bypass of remote-login access control because the same AES key is used for different customers' installations. If an attacker were to know this key, they could decrypt protected information stored in registry or configuration files or decryption of the Unattended Access password to the system (which allows for remote login to the system). 建議動作：Apply updates per vendor instructions.。

### **[EXPLOITED]** `CVE-2019-6340` — Drupal Core Remote Code Execution Vulnerability

- Installed: `apport-core-dump-handler` (version `2.28.1-0ubuntu3.8`, vendor `Ubuntu Developers <ubuntu-devel-discuss@lists.ubuntu.com>`)
- KEV vendor / product: Drupal / Core
- Date added to KEV: 2022-03-25
- CISA due date: 2022-04-15
- Match: `vendor+product+fuzzy` (score 100)
- CWEs: CWE-502

In Drupal Core, some field types do not properly sanitize data from non-form sources. This can lead to arbitrary PHP code execution in some cases. 建議動作：Apply updates per vendor instructions.。

### **[EXPLOITED]** `CVE-2019-6340` — Drupal Core Remote Code Execution Vulnerability

- Installed: `at-spi2-core` (version `2.52.0-1build1`, vendor `Ubuntu Developers <ubuntu-devel-discuss@lists.ubuntu.com>`)
- KEV vendor / product: Drupal / Core
- Date added to KEV: 2022-03-25
- CISA due date: 2022-04-15
- Match: `vendor+product+fuzzy` (score 100)
- CWEs: CWE-502

In Drupal Core, some field types do not properly sanitize data from non-form sources. This can lead to arbitrary PHP code execution in some cases. 建議動作：Apply updates per vendor instructions.。

### **[EXPLOITED]** `CVE-2019-6340` — Drupal Core Remote Code Execution Vulnerability

- Installed: `fonts-dejavu-core` (version `2.37-8`, vendor `Ubuntu Developers <ubuntu-devel-discuss@lists.ubuntu.com>`)
- KEV vendor / product: Drupal / Core
- Date added to KEV: 2022-03-25
- CISA due date: 2022-04-15
- Match: `vendor+product+fuzzy` (score 100)
- CWEs: CWE-502

In Drupal Core, some field types do not properly sanitize data from non-form sources. This can lead to arbitrary PHP code execution in some cases. 建議動作：Apply updates per vendor instructions.。

### **[EXPLOITED]** `CVE-2019-6340` — Drupal Core Remote Code Execution Vulnerability

- Installed: `libevent-core-2.1-7t64` (version `2.1.12-stable-9ubuntu2`, vendor `Ubuntu Developers <ubuntu-devel-discuss@lists.ubuntu.com>`)
- KEV vendor / product: Drupal / Core
- Date added to KEV: 2022-03-25
- CISA due date: 2022-04-15
- Match: `vendor+product+fuzzy` (score 100)
- CWEs: CWE-502

In Drupal Core, some field types do not properly sanitize data from non-form sources. This can lead to arbitrary PHP code execution in some cases. 建議動作：Apply updates per vendor instructions.。

### **[EXPLOITED]** `CVE-2019-6340` — Drupal Core Remote Code Execution Vulnerability

- Installed: `libmaven3-core-java` (version `3.8.7-2`, vendor `Ubuntu Developers <ubuntu-devel-discuss@lists.ubuntu.com>`)
- KEV vendor / product: Drupal / Core
- Date added to KEV: 2022-03-25
- CISA due date: 2022-04-15
- Match: `vendor+product+fuzzy` (score 100)
- CWEs: CWE-502

In Drupal Core, some field types do not properly sanitize data from non-form sources. This can lead to arbitrary PHP code execution in some cases. 建議動作：Apply updates per vendor instructions.。

### **[EXPLOITED]** `CVE-2019-6340` — Drupal Core Remote Code Execution Vulnerability

- Installed: `ubuntu-release-upgrader-core` (version `1:24.04.28`, vendor `Ubuntu Developers <ubuntu-devel-discuss@lists.ubuntu.com>`)
- KEV vendor / product: Drupal / Core
- Date added to KEV: 2022-03-25
- CISA due date: 2022-04-15
- Match: `vendor+product+fuzzy` (score 100)
- CWEs: CWE-502

In Drupal Core, some field types do not properly sanitize data from non-form sources. This can lead to arbitrary PHP code execution in some cases. 建議動作：Apply updates per vendor instructions.。

### **[EXPLOITED]** `CVE-2019-6340` — Drupal Core Remote Code Execution Vulnerability

- Installed: `update-manager-core` (version `1:24.04.12`, vendor `Ubuntu Developers <ubuntu-devel-discuss@lists.ubuntu.com>`)
- KEV vendor / product: Drupal / Core
- Date added to KEV: 2022-03-25
- CISA due date: 2022-04-15
- Match: `vendor+product+fuzzy` (score 100)
- CWEs: CWE-502

In Drupal Core, some field types do not properly sanitize data from non-form sources. This can lead to arbitrary PHP code execution in some cases. 建議動作：Apply updates per vendor instructions.。

### **[EXPLOITED]** `CVE-2020-11023` — JQuery Cross-Site Scripting (XSS) Vulnerability

- Installed: `libjs-jquery` (version `3.6.1+dfsg+~3.5.14-1`, vendor `Ubuntu Developers <ubuntu-devel-discuss@lists.ubuntu.com>`)
- KEV vendor / product: JQuery / JQuery
- Date added to KEV: 2025-01-23
- CISA due date: 2025-02-13
- Match: `vendor+product+fuzzy` (score 100)
- CWEs: CWE-79

JQuery contains a persistent cross-site scripting (XSS) vulnerability. When passing maliciously formed, untrusted input enclosed in HTML tags, JQuery's DOM manipulators can execute untrusted code in the context of the user's browser. 建議動作：Apply mitigations per vendor instructions or discontinue use of the product if mitigations are unavailable.。

### **[EXPLOITED]** `CVE-2020-28949` — PEAR Archive_Tar Deserialization of Untrusted Data Vulnerability

- Installed: `tar` (version `1.35+dfsg-3build1`, vendor `Ubuntu Developers <ubuntu-devel-discuss@lists.ubuntu.com>`)
- KEV vendor / product: PEAR / Archive_Tar
- Date added to KEV: 2022-08-25
- CISA due date: 2022-09-15
- Match: `vendor+product+fuzzy` (score 100)
- CWEs: CWE-74

PEAR Archive_Tar allows an unserialization attack because phar: is blocked but PHAR: is not blocked. PEAR stands for PHP Extension and Application Repository and it is an open-source framework and distribution system for reusable PHP components with known usage in third-party products such as Drupal Core and Red Hat Linux. 建議動作：Apply updates per vendor instructions.。

### **[EXPLOITED]** `CVE-2020-36193` — PEAR Archive_Tar Improper Link Resolution Vulnerability

- Installed: `tar` (version `1.35+dfsg-3build1`, vendor `Ubuntu Developers <ubuntu-devel-discuss@lists.ubuntu.com>`)
- KEV vendor / product: PEAR / Archive_Tar
- Date added to KEV: 2022-08-25
- CISA due date: 2022-09-15
- Match: `vendor+product+fuzzy` (score 100)
- CWEs: CWE-22, CWE-59

PEAR Archive_Tar Tar.php allows write operations with directory traversal due to inadequate checking of symbolic links. PEAR stands for PHP Extension and Application Repository and it is an open-source framework and distribution system for reusable PHP components with known usage in third-party products such as Drupal Core and Red Hat Linux. 建議動作：Apply updates per vendor instructions.。

### **[EXPLOITED]** `CVE-2021-3156` — Sudo Heap-Based Buffer Overflow Vulnerability

- Installed: `sudo` (version `1.9.15p5-3ubuntu5.24.04.2`, vendor `Ubuntu Developers <ubuntu-devel-discuss@lists.ubuntu.com>`)
- KEV vendor / product: Sudo / Sudo
- Date added to KEV: 2022-04-06
- CISA due date: 2022-04-27
- Match: `vendor+product+fuzzy` (score 100)
- CWEs: CWE-122, CWE-193

Sudo contains an off-by-one error that can result in a heap-based buffer overflow, which allows for privilege escalation. 建議動作：Apply updates per vendor instructions.。

### **[EXPLOITED]** `CVE-2023-20867` — VMware Tools Authentication Bypass Vulnerability

- Installed: `libpng-tools` (version `1.6.43-5ubuntu0.5`, vendor `Ubuntu Developers <ubuntu-devel-discuss@lists.ubuntu.com>`)
- KEV vendor / product: VMware / Tools
- Date added to KEV: 2023-06-23
- CISA due date: 2023-07-14
- Match: `vendor+product+fuzzy` (score 100)
- CWEs: CWE-287

VMware Tools contains an authentication bypass vulnerability in the vgauth module. A fully compromised ESXi host can force VMware Tools to fail to authenticate host-to-guest operations, impacting the confidentiality and integrity of the guest virtual machine. An attacker must have root access over ESXi to exploit this vulnerability. 建議動作：Apply updates per vendor instructions.。

### **[EXPLOITED]** `CVE-2023-20867` — VMware Tools Authentication Bypass Vulnerability

- Installed: `linux-tools-6.8.0-110` (version `6.8.0-110.110`, vendor `Ubuntu Kernel Team <kernel-team@lists.ubuntu.com>`)
- KEV vendor / product: VMware / Tools
- Date added to KEV: 2023-06-23
- CISA due date: 2023-07-14
- Match: `vendor+product+fuzzy` (score 100)
- CWEs: CWE-287

VMware Tools contains an authentication bypass vulnerability in the vgauth module. A fully compromised ESXi host can force VMware Tools to fail to authenticate host-to-guest operations, impacting the confidentiality and integrity of the guest virtual machine. An attacker must have root access over ESXi to exploit this vulnerability. 建議動作：Apply updates per vendor instructions.。

### **[EXPLOITED]** `CVE-2023-20867` — VMware Tools Authentication Bypass Vulnerability

- Installed: `linux-tools-6.8.0-110-generic` (version `6.8.0-110.110`, vendor `Ubuntu Kernel Team <kernel-team@lists.ubuntu.com>`)
- KEV vendor / product: VMware / Tools
- Date added to KEV: 2023-06-23
- CISA due date: 2023-07-14
- Match: `vendor+product+fuzzy` (score 100)
- CWEs: CWE-287

VMware Tools contains an authentication bypass vulnerability in the vgauth module. A fully compromised ESXi host can force VMware Tools to fail to authenticate host-to-guest operations, impacting the confidentiality and integrity of the guest virtual machine. An attacker must have root access over ESXi to exploit this vulnerability. 建議動作：Apply updates per vendor instructions.。

### **[EXPLOITED]** `CVE-2023-20867` — VMware Tools Authentication Bypass Vulnerability

- Installed: `linux-tools-common` (version `6.8.0-110.110`, vendor `Ubuntu Kernel Team <kernel-team@lists.ubuntu.com>`)
- KEV vendor / product: VMware / Tools
- Date added to KEV: 2023-06-23
- CISA due date: 2023-07-14
- Match: `vendor+product+fuzzy` (score 100)
- CWEs: CWE-287

VMware Tools contains an authentication bypass vulnerability in the vgauth module. A fully compromised ESXi host can force VMware Tools to fail to authenticate host-to-guest operations, impacting the confidentiality and integrity of the guest virtual machine. An attacker must have root access over ESXi to exploit this vulnerability. 建議動作：Apply updates per vendor instructions.。

### **[EXPLOITED]** `CVE-2023-20867` — VMware Tools Authentication Bypass Vulnerability

- Installed: `linux-tools-generic` (version `6.8.0-110.110`, vendor `Ubuntu Kernel Team <kernel-team@lists.ubuntu.com>`)
- KEV vendor / product: VMware / Tools
- Date added to KEV: 2023-06-23
- CISA due date: 2023-07-14
- Match: `vendor+product+fuzzy` (score 100)
- CWEs: CWE-287

VMware Tools contains an authentication bypass vulnerability in the vgauth module. A fully compromised ESXi host can force VMware Tools to fail to authenticate host-to-guest operations, impacting the confidentiality and integrity of the guest virtual machine. An attacker must have root access over ESXi to exploit this vulnerability. 建議動作：Apply updates per vendor instructions.。

### **[EXPLOITED]** `CVE-2023-20867` — VMware Tools Authentication Bypass Vulnerability

- Installed: `packagekit-tools` (version `1.2.8-2ubuntu1.4`, vendor `Ubuntu Developers <ubuntu-devel-discuss@lists.ubuntu.com>`)
- KEV vendor / product: VMware / Tools
- Date added to KEV: 2023-06-23
- CISA due date: 2023-07-14
- Match: `vendor+product+fuzzy` (score 100)
- CWEs: CWE-287

VMware Tools contains an authentication bypass vulnerability in the vgauth module. A fully compromised ESXi host can force VMware Tools to fail to authenticate host-to-guest operations, impacting the confidentiality and integrity of the guest virtual machine. An attacker must have root access over ESXi to exploit this vulnerability. 建議動作：Apply updates per vendor instructions.。

### **[EXPLOITED]** `CVE-2023-20867` — VMware Tools Authentication Bypass Vulnerability

- Installed: `squashfs-tools` (version `1:4.6.1-1build1`, vendor `Ubuntu Developers <ubuntu-devel-discuss@lists.ubuntu.com>`)
- KEV vendor / product: VMware / Tools
- Date added to KEV: 2023-06-23
- CISA due date: 2023-07-14
- Match: `vendor+product+fuzzy` (score 100)
- CWEs: CWE-287

VMware Tools contains an authentication bypass vulnerability in the vgauth module. A fully compromised ESXi host can force VMware Tools to fail to authenticate host-to-guest operations, impacting the confidentiality and integrity of the guest virtual machine. An attacker must have root access over ESXi to exploit this vulnerability. 建議動作：Apply updates per vendor instructions.。

### **[EXPLOITED]** `CVE-2024-23692` — Rejetto HTTP File Server Improper Neutralization of Special Elements Used in a Template Engine Vulnerability

- Installed: `file` (version `1:5.45-3build1`, vendor `Ubuntu Developers <ubuntu-devel-discuss@lists.ubuntu.com>`)
- KEV vendor / product: Rejetto / HTTP File Server
- Date added to KEV: 2024-07-09
- CISA due date: 2024-07-30
- Match: `vendor+product+fuzzy` (score 100)
- CWEs: CWE-1336

Rejetto HTTP File Server contains an improper neutralization of special elements used in a template engine vulnerability. This allows a remote, unauthenticated attacker to execute commands on the affected system by sending a specially crafted HTTP request. 建議動作：Apply mitigations per vendor instructions or discontinue use of the product if mitigations are unavailable.。

### **[EXPLOITED]** `CVE-2025-11953` — React Native Community CLI OS Command Injection Vulnerability

- Installed: `libcommons-cli-java` (version `1.6.0-1`, vendor `Ubuntu Developers <ubuntu-devel-discuss@lists.ubuntu.com>`)
- KEV vendor / product: React Native Community / CLI
- Date added to KEV: 2026-02-05
- CISA due date: 2026-02-26
- Match: `vendor+product+fuzzy` (score 100)
- CWEs: CWE-78

React Native Community CLI contains an OS command injection vulnerability which could allow unauthenticated network attackers to send POST requests to the Metro Development Server and run arbitrary executables via a vulnerable endpoint exposed by the server. On Windows, attackers can also execute arbitrary shell commands with fully controlled arguments. 建議動作：Apply mitigations per vendor instructions, follow applicable BOD 22-01 guidance for cloud services, or discontinue use of the product if mitigations are unavailable.。

### **[EXPLOITED]** `CVE-2025-32463` — Sudo Inclusion of Functionality from Untrusted Control Sphere Vulnerability

- Installed: `sudo` (version `1.9.15p5-3ubuntu5.24.04.2`, vendor `Ubuntu Developers <ubuntu-devel-discuss@lists.ubuntu.com>`)
- KEV vendor / product: Sudo / Sudo
- Date added to KEV: 2025-09-29
- CISA due date: 2025-10-20
- Match: `vendor+product+fuzzy` (score 100)
- CWEs: CWE-829

Sudo contains an inclusion of functionality from untrusted control sphere vulnerability. This vulnerability could allow local attacker to leverage sudo’s -R (--chroot) option to run arbitrary commands as root, even if they are not listed in the sudoers file. 建議動作：Apply mitigations per vendor instructions, follow applicable BOD 22-01 guidance for cloud services, or discontinue use of the product if mitigations are unavailable.。

### **[EXPLOITED]** `CVE-2025-48384` — Git Link Following Vulnerability

- Installed: `git` (version `1:2.43.0-1ubuntu7.3`, vendor `Ubuntu Developers <ubuntu-devel-discuss@lists.ubuntu.com>`)
- KEV vendor / product: Git / Git
- Date added to KEV: 2025-08-25
- CISA due date: 2025-09-15
- Match: `vendor+product+fuzzy` (score 100)
- CWEs: CWE-59, CWE-436

Git contains a link following vulnerability that stems from Git’s inconsistent handling of carriage return characters in configuration files. 建議動作：Apply mitigations per vendor instructions, follow applicable BOD 22-01 guidance for cloud services, or discontinue use of the product if mitigations are unavailable.。

### **[EXPLOITED]** `CVE-2025-48384` — Git Link Following Vulnerability

- Installed: `git-man` (version `1:2.43.0-1ubuntu7.3`, vendor `Ubuntu Developers <ubuntu-devel-discuss@lists.ubuntu.com>`)
- KEV vendor / product: Git / Git
- Date added to KEV: 2025-08-25
- CISA due date: 2025-09-15
- Match: `vendor+product+fuzzy` (score 100)
- CWEs: CWE-59, CWE-436

Git contains a link following vulnerability that stems from Git’s inconsistent handling of carriage return characters in configuration files. 建議動作：Apply mitigations per vendor instructions, follow applicable BOD 22-01 guidance for cloud services, or discontinue use of the product if mitigations are unavailable.。

### **[EXPLOITED]** `CVE-2025-48543` — Android Runtime Use-After-Free Vulnerability

- Installed: `libpam-runtime` (version `1.5.3-5ubuntu5.5`, vendor `Ubuntu Developers <ubuntu-devel-discuss@lists.ubuntu.com>`)
- KEV vendor / product: Android / Runtime
- Date added to KEV: 2025-09-04
- CISA due date: 2025-09-25
- Match: `vendor+product+fuzzy` (score 100)

Android Runtime contains a use-after-free vulnerability potentially allowing a chrome sandbox escape leading to local privilege escalation. 建議動作：Apply mitigations per vendor instructions, follow applicable BOD 22-01 guidance for cloud services, or discontinue use of the product if mitigations are unavailable.。

### **[EXPLOITED]** `CVE-2025-48543` — Android Runtime Use-After-Free Vulnerability

- Installed: `uuid-runtime` (version `2.39.3-9ubuntu6.5`, vendor `Ubuntu Developers <ubuntu-devel-discuss@lists.ubuntu.com>`)
- KEV vendor / product: Android / Runtime
- Date added to KEV: 2025-09-04
- CISA due date: 2025-09-25
- Match: `vendor+product+fuzzy` (score 100)

Android Runtime contains a use-after-free vulnerability potentially allowing a chrome sandbox escape leading to local privilege escalation. 建議動作：Apply mitigations per vendor instructions, follow applicable BOD 22-01 guidance for cloud services, or discontinue use of the product if mitigations are unavailable.。

### **[EXPLOITED]** `CVE-2025-48543` — Android Runtime Use-After-Free Vulnerability

- Installed: `vim-runtime` (version `2:9.1.0016-1ubuntu7.11`, vendor `Ubuntu Developers <ubuntu-devel-discuss@lists.ubuntu.com>`)
- KEV vendor / product: Android / Runtime
- Date added to KEV: 2025-09-04
- CISA due date: 2025-09-25
- Match: `vendor+product+fuzzy` (score 100)

Android Runtime contains a use-after-free vulnerability potentially allowing a chrome sandbox escape leading to local privilege escalation. 建議動作：Apply mitigations per vendor instructions, follow applicable BOD 22-01 guidance for cloud services, or discontinue use of the product if mitigations are unavailable.。

### **[EXPLOITED]** `CVE-2026-3502` — TrueConf Client Download of Code Without Integrity Check Vulnerability

- Installed: `gpg-wks-client` (version `2.4.4-2ubuntu17.4`, vendor `Ubuntu Developers <ubuntu-devel-discuss@lists.ubuntu.com>`)
- KEV vendor / product: TrueConf / Client
- Date added to KEV: 2026-04-02
- CISA due date: 2026-04-16
- Match: `vendor+product+fuzzy` (score 100)
- CWEs: CWE-494

TrueConf Client contains a download of code without integrity check vulnerability. An attacker who is able to influence the update delivery path can substitute a tampered update payload. If the payload is executed or installed by the updater, this may result in arbitrary code execution in the context of the updating process or user. 建議動作：Apply mitigations per vendor instructions, follow applicable BOD 22-01 guidance for cloud services, or discontinue use of the product if mitigations are unavailable.。

### **[EXPLOITED]** `CVE-2026-3502` — TrueConf Client Download of Code Without Integrity Check Vulnerability

- Installed: `landscape-client` (version `24.02-0ubuntu5.7`, vendor `Ubuntu Developers <ubuntu-devel-discuss@lists.ubuntu.com>`)
- KEV vendor / product: TrueConf / Client
- Date added to KEV: 2026-04-02
- CISA due date: 2026-04-16
- Match: `vendor+product+fuzzy` (score 100)
- CWEs: CWE-494

TrueConf Client contains a download of code without integrity check vulnerability. An attacker who is able to influence the update delivery path can substitute a tampered update payload. If the payload is executed or installed by the updater, this may result in arbitrary code execution in the context of the updating process or user. 建議動作：Apply mitigations per vendor instructions, follow applicable BOD 22-01 guidance for cloud services, or discontinue use of the product if mitigations are unavailable.。

### **[EXPLOITED]** `CVE-2026-3502` — TrueConf Client Download of Code Without Integrity Check Vulnerability

- Installed: `openssh-client` (version `1:9.6p1-3ubuntu13.15`, vendor `Ubuntu Developers <ubuntu-devel-discuss@lists.ubuntu.com>`)
- KEV vendor / product: TrueConf / Client
- Date added to KEV: 2026-04-02
- CISA due date: 2026-04-16
- Match: `vendor+product+fuzzy` (score 100)
- CWEs: CWE-494

TrueConf Client contains a download of code without integrity check vulnerability. An attacker who is able to influence the update delivery path can substitute a tampered update payload. If the payload is executed or installed by the updater, this may result in arbitrary code execution in the context of the updating process or user. 建議動作：Apply mitigations per vendor instructions, follow applicable BOD 22-01 guidance for cloud services, or discontinue use of the product if mitigations are unavailable.。

### **[EXPLOITED]** `CVE-2026-3502` — TrueConf Client Download of Code Without Integrity Check Vulnerability

- Installed: `ubuntu-pro-client` (version `37.1ubuntu0~24.04`, vendor `Ubuntu Developers <ubuntu-devel-discuss@lists.ubuntu.com>`)
- KEV vendor / product: TrueConf / Client
- Date added to KEV: 2026-04-02
- CISA due date: 2026-04-16
- Match: `vendor+product+fuzzy` (score 100)
- CWEs: CWE-494

TrueConf Client contains a download of code without integrity check vulnerability. An attacker who is able to influence the update delivery path can substitute a tampered update payload. If the payload is executed or installed by the updater, this may result in arbitrary code execution in the context of the updating process or user. 建議動作：Apply mitigations per vendor instructions, follow applicable BOD 22-01 guidance for cloud services, or discontinue use of the product if mitigations are unavailable.。

### **[EXPLOITED]** `CVE-2026-3502` — TrueConf Client Download of Code Without Integrity Check Vulnerability

- Installed: `ubuntu-pro-client-l10n` (version `37.1ubuntu0~24.04`, vendor `Ubuntu Developers <ubuntu-devel-discuss@lists.ubuntu.com>`)
- KEV vendor / product: TrueConf / Client
- Date added to KEV: 2026-04-02
- CISA due date: 2026-04-16
- Match: `vendor+product+fuzzy` (score 100)
- CWEs: CWE-494

TrueConf Client contains a download of code without integrity check vulnerability. An attacker who is able to influence the update delivery path can substitute a tampered update payload. If the payload is executed or installed by the updater, this may result in arbitrary code execution in the context of the updating process or user. 建議動作：Apply mitigations per vendor instructions, follow applicable BOD 22-01 guidance for cloud services, or discontinue use of the product if mitigations are unavailable.。

### **[EXPLOITED]** `CVE-2021-3560` — Red Hat Polkit Incorrect Authorization Vulnerability

- Installed: `polkitd` (version `124-2ubuntu1.24.04.3`, vendor `Ubuntu Developers <ubuntu-devel-discuss@lists.ubuntu.com>`)
- KEV vendor / product: Red Hat / Polkit
- Date added to KEV: 2023-05-12
- CISA due date: 2023-06-02
- Match: `vendor+product+fuzzy` (score 92)
- CWEs: CWE-863

Red Hat Polkit contains an incorrect authorization vulnerability through the bypassing of credential checks for D-Bus requests, allowing for privilege escalation. 建議動作：Apply updates per vendor instructions.。

### **[EXPLOITED]** `CVE-2021-4034` — Red Hat Polkit Out-of-Bounds Read and Write Vulnerability

- Installed: `polkitd` (version `124-2ubuntu1.24.04.3`, vendor `Ubuntu Developers <ubuntu-devel-discuss@lists.ubuntu.com>`)
- KEV vendor / product: Red Hat / Polkit
- Date added to KEV: 2022-06-27
- CISA due date: 2022-07-18
- Match: `vendor+product+fuzzy` (score 92)
- CWEs: CWE-787

The Red Hat polkit pkexec utility contains an out-of-bounds read and write vulnerability that allows for privilege escalation with administrative rights. 建議動作：Apply updates per vendor instructions.。

## How to read this report

Every entry above maps to a vulnerability that **CISA has confirmed is being exploited in the wild**. A match here means you have software from the same product family — it does *not* prove your specific version is vulnerable. Verify each finding against the vendor's advisory page before acting. Ransomware-linked entries should be patched first.
