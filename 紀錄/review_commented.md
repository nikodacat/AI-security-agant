# CVE Scan Report

_Generated 2026-04-29 17:34 UTC_

## Summary

- Host: `linux` (scanned at 2026-04-29T17:27:58+00:00)
- Inventory: **676** packages
- KEV catalog: **1585** entries (version 2026.04.28, released 2026-04-28T17:29:22.212Z)
- Findings: **47** (21 unique CVEs across 36 packages)
- Ransomware-linked CVEs hit: **8** — treat as P0
- Explanation backend: `claude`

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

這個漏洞讓攻擊者能夠在您的 Windows 系統上執行惡意程式，從而取得系統管理員等級的權限，進而完全控制您的電腦、竊取資料或安裝勒索軟體。您必須立即安裝微軟發布的安全性更新來修補此漏洞。這個漏洞已被勒索軟體組織實際利用，且攻擊者只需在本機執行程式即可得逞，不需要您點擊任何連結,因此風險極高且緊急。請優先處理此更新，避免成為勒索軟體攻擊的受害者。

### **[RANSOMWARE]** `CVE-2018-7602` — Drupal Core Remote Code Execution Vulnerability

- Installed: `apport-core-dump-handler` (version `2.28.1-0ubuntu3.8`, vendor `Ubuntu Developers <ubuntu-devel-discuss@lists.ubuntu.com>`)
- KEV vendor / product: Drupal / Core
- Date added to KEV: 2022-04-13
- CISA due date: 2022-05-04
- Match: `vendor+product+fuzzy` (score 100)

這個 Drupal 核心漏洞讓遠端攻擊者可以在您的網站伺服器上執行任意程式碼,無需登入帳號即可完全掌控您的網站,竊取資料庫資料、植入後門或散布勒索軟體。您必須立即將 Drupal 更新至官方發布的安全修補版本。此漏洞已被勒索軟體組織實際利用,且攻擊者可透過網路遠端發動攻擊,不需要您進行任何操作就能入侵,危險性極高。如果您正在運行 Drupal 網站,請將此更新列為最高優先事項,延遲修補可能導致嚴重的資料外洩或勒索攻擊。

### **[RANSOMWARE]** `CVE-2018-7602` — Drupal Core Remote Code Execution Vulnerability

- Installed: `at-spi2-core` (version `2.52.0-1build1`, vendor `Ubuntu Developers <ubuntu-devel-discuss@lists.ubuntu.com>`)
- KEV vendor / product: Drupal / Core
- Date added to KEV: 2022-04-13
- CISA due date: 2022-05-04
- Match: `vendor+product+fuzzy` (score 100)

這個 Drupal 核心漏洞允許攻擊者從遠端在您的伺服器上執行惡意程式碼,可能導致整個網站被接管、敏感資料遭竊或被植入勒索軟體。請立即按照 Drupal 官方指示安裝最新的安全性更新。由於此漏洞已被勒索軟體集團積極利用,且攻擊者可透過多種方式遠端發動攻擊而無需您的互動,修補的急迫性極高。若您的系統上有運行 Drupal 網站,每一分鐘的延遲都可能讓攻擊者有機可乘。

### **[RANSOMWARE]** `CVE-2018-7602` — Drupal Core Remote Code Execution Vulnerability

- Installed: `fonts-dejavu-core` (version `2.37-8`, vendor `Ubuntu Developers <ubuntu-devel-discuss@lists.ubuntu.com>`)
- KEV vendor / product: Drupal / Core
- Date added to KEV: 2022-04-13
- CISA due date: 2022-05-04
- Match: `vendor+product+fuzzy` (score 100)

此 Drupal 漏洞讓駭客能夠透過網路遠端在您的伺服器執行任意指令,進而竊取所有網站資料、修改內容或加密檔案進行勒索。您需要馬上依照 Drupal 維護團隊的指示套用安全性修補程式。這個漏洞不需要使用者點擊或操作即可被利用,且已有勒索軟體組織實際運用它來發動攻擊,時間緊迫。如果您管理的系統有安裝 Drupal,請將更新作業視為緊急任務立即執行,以免遭受入侵。

### **[RANSOMWARE]** `CVE-2018-7602` — Drupal Core Remote Code Execution Vulnerability

- Installed: `libevent-core-2.1-7t64` (version `2.1.12-stable-9ubuntu2`, vendor `Ubuntu Developers <ubuntu-devel-discuss@lists.ubuntu.com>`)
- KEV vendor / product: Drupal / Core
- Date added to KEV: 2022-04-13
- CISA due date: 2022-05-04
- Match: `vendor+product+fuzzy` (score 100)

Drupal 核心的這個漏洞使攻擊者可以從網際網路遠端控制您的網站伺服器,執行任何惡意程式,包括安裝勒索軟體、竊取使用者帳密或癱瘓整個網站。請即刻更新至 Drupal 官方發布的安全版本。此漏洞因為可被遠端利用且已遭勒索軟體組織實戰使用,危險等級極高,攻擊過程完全不需要您進行任何動作。延遲修補可能在數小時內就讓您的網站淪陷,務必優先處理這項更新。

### **[RANSOMWARE]** `CVE-2018-7602` — Drupal Core Remote Code Execution Vulnerability

- Installed: `libmaven3-core-java` (version `3.8.7-2`, vendor `Ubuntu Developers <ubuntu-devel-discuss@lists.ubuntu.com>`)
- KEV vendor / product: Drupal / Core
- Date added to KEV: 2022-04-13
- CISA due date: 2022-05-04
- Match: `vendor+product+fuzzy` (score 100)

這個 Drupal 漏洞讓駭客無需登入就能遠端在您的網站伺服器上執行惡意程式,可能導致資料外洩、網站被竄改或遭勒索軟體加密所有檔案。您必須立刻依 Drupal 官方安全公告的步驟進行更新修補。由於勒索軟體集團已實際運用此漏洞進行攻擊,且攻擊可完全自動化執行不需受害者互動,風險非常緊急。若您有運行 Drupal 站台,每延遲一刻都增加被入侵的可能性,請將此更新列為當務之急。

### **[RANSOMWARE]** `CVE-2018-7602` — Drupal Core Remote Code Execution Vulnerability

- Installed: `ubuntu-release-upgrader-core` (version `1:24.04.28`, vendor `Ubuntu Developers <ubuntu-devel-discuss@lists.ubuntu.com>`)
- KEV vendor / product: Drupal / Core
- Date added to KEV: 2022-04-13
- CISA due date: 2022-05-04
- Match: `vendor+product+fuzzy` (score 100)

此 Drupal 核心漏洞可讓遠端攻擊者透過多種攻擊手法在您的網站伺服器執行任意程式碼,完全掌控系統後可竊取資料庫、散播惡意軟體或部署勒索軟體加密您的所有資料。請立即套用 Drupal 官方提供的安全性更新程式。這個漏洞已被勒索軟體組織用於實際攻擊,且屬於遠端可利用的高危漏洞,攻擊者不需要您的任何操作就能入侵。如果您的環境中有 Drupal 網站正在運行,這項更新刻不容緩,應立即執行以避免災難性後果。

### **[RANSOMWARE]** `CVE-2018-7602` — Drupal Core Remote Code Execution Vulnerability

- Installed: `update-manager-core` (version `1:24.04.12`, vendor `Ubuntu Developers <ubuntu-devel-discuss@lists.ubuntu.com>`)
- KEV vendor / product: Drupal / Core
- Date added to KEV: 2022-04-13
- CISA due date: 2022-05-04
- Match: `vendor+product+fuzzy` (score 100)

Drupal 核心的這項漏洞允許駭客從遠端位置對您的網站發動攻擊並執行惡意程式碼,可能造成網站資料被竊、系統被植入後門或檔案遭勒索軟體加密鎖住。您應立即遵循 Drupal 安全團隊的指引安裝修補更新。此漏洞因已被勒索軟體犯罪組織實際使用,且可透過遠端無需使用者互動即可觸發,屬於極高風險等級。若您負責管理任何 Drupal 網站,請把這個更新當作最優先任務馬上處理,拖延可能在短時間內導致嚴重資安事件。

### **[EXPLOITED]** `CVE-2012-1889` — Microsoft XML Core Services Memory Corruption Vulnerability

- Installed: `xml-core` (version `0.19`, vendor `Ubuntu Developers <ubuntu-devel-discuss@lists.ubuntu.com>`)
- KEV vendor / product: Microsoft / XML Core Services
- Date added to KEV: 2022-06-08
- CISA due date: 2022-06-22
- Match: `vendor+product+fuzzy` (score 100)
- CWEs: CWE-119

這個 Microsoft XML 核心服務的記憶體損毀漏洞讓攻擊者可以透過精心製作的網頁或文件,在您瀏覽或開啟時遠端執行惡意程式碼,進而控制您的電腦並竊取資料。您必須立即透過 Windows Update 安裝微軟發布的安全性更新。雖然目前尚未被標記為勒索軟體組織慣用手法,但這個漏洞允許遠端程式碼執行,只要您開啟惡意網頁或檔案就可能中招,風險仍然很高。請盡快完成更新,特別是如果您經常瀏覽網頁或處理來自外部的文件檔案。

### **[EXPLOITED]** `CVE-2014-0160` — OpenSSL Information Disclosure Vulnerability

- Installed: `openssl` (version `3.0.13-0ubuntu3.9`, vendor `Ubuntu Developers <ubuntu-devel-discuss@lists.ubuntu.com>`)
- KEV vendor / product: OpenSSL / OpenSSL
- Date added to KEV: 2022-05-04
- CISA due date: 2022-05-25
- Match: `vendor+product+fuzzy` (score 100)
- CWEs: CWE-125

這個 OpenSSL「心淌血」(Heartbleed) 漏洞讓遠端攻擊者可以從您的伺服器記憶體中竊取敏感資訊,包括密碼、加密金鑰、信用卡號碼及其他機密資料,且攻擊過程不會留下任何痕跡。您必須立即將 OpenSSL 更新至修補版本,並在更新後重新產生所有 SSL/TLS 憑證和變更相關密碼。雖然目前未被標記為勒索軟體常用手法,但此漏洞可被遠端利用且影響極廣,攻擊者可輕易取得系統最重要的機密資訊。若您的系統有對外提供網路服務,這個更新極為緊急,延遲修補可能導致大量敏感資料外洩。

### **[EXPLOITED]** `CVE-2014-0160` — OpenSSL Information Disclosure Vulnerability

- Installed: `python3-openssl` (version `23.2.0-1ubuntu0.1`, vendor `Ubuntu Developers <ubuntu-devel-discuss@lists.ubuntu.com>`)
- KEV vendor / product: OpenSSL / OpenSSL
- Date added to KEV: 2022-05-04
- CISA due date: 2022-05-25
- Match: `vendor+product+fuzzy` (score 100)
- CWEs: CWE-125

此 OpenSSL「心淌血」漏洞使駭客能從遠端讀取伺服器記憶體內容,竊取使用者密碼、私密金鑰、個人資料等敏感資訊,而且攻擊行為難以被偵測發現。請立即更新 OpenSSL 及相關套件至安全版本,並在修補後更換所有 SSL 憑證與重設受影響帳號的密碼。雖未被列為勒索軟體組織主要工具,但這個漏洞允許遠端攻擊且無需任何使用者操作,可能導致大規模資料外洩。如果您的系統有提供加密連線服務(HTTPS、VPN 等),務必盡快完成更新與憑證更換作業。

### **[EXPLOITED]** `CVE-2014-6278` — GNU Bash OS Command Injection Vulnerability

- Installed: `bash` (version `5.2.21-2ubuntu4`, vendor `Ubuntu Developers <ubuntu-devel-discuss@lists.ubuntu.com>`)
- KEV vendor / product: GNU / GNU Bash
- Date added to KEV: 2025-10-02
- CISA due date: 2025-10-23
- Match: `vendor+product+fuzzy` (score 100)
- CWEs: CWE-78

這個 GNU Bash「破殼」(Shellshock) 漏洞讓遠端攻擊者可以透過精心設計的環境變數注入並執行任意系統指令,完全控制您的伺服器或電腦。您必須立即依照官方指示更新 Bash 至安全版本,若無法取得更新則應依循供應商的緩解措施或停用相關功能。雖然目前未被標記為勒索軟體慣用手法,但此漏洞可被遠端利用來執行任何指令,特別危險於有對外提供網頁服務(CGI)或接受外部輸入的系統。如果您的 Linux/Unix 系統有連接網路,這個更新非常重要且應盡快處理,以防攻擊者取得系統控制權。

### **[EXPLOITED]** `CVE-2017-0022` — Microsoft XML Core Services Information Disclosure Vulnerability

- Installed: `xml-core` (version `0.19`, vendor `Ubuntu Developers <ubuntu-devel-discuss@lists.ubuntu.com>`)
- KEV vendor / product: Microsoft / XML Core Services
- Date added to KEV: 2022-05-24
- CISA due date: 2022-06-14
- Match: `vendor+product+fuzzy` (score 100)
- CWEs: CWE-200

這個 Microsoft XML 核心服務漏洞讓攻擊者可以透過惡意網站探測您電腦硬碟上的檔案是否存在,進而洩露您的檔案結構、已安裝軟體及其他敏感資訊,為後續攻擊鋪路。您應立即透過 Windows Update 安裝微軟發布的安全性修補程式。雖然此漏洞目前未被勒索軟體組織廣泛使用,但攻擊者只需引誘您瀏覽精心設計的惡意網頁即可取得您的系統資訊,風險不容忽視。請盡快完成更新,特別是如果您經常瀏覽各種網站或點擊連結,以避免個人資訊被探查洩露。

### **[EXPLOITED]** `CVE-2019-18988` — TeamViewer Desktop Bypass Remote Login Vulnerability

- Installed: `gsettings-desktop-schemas` (version `46.1-0ubuntu1`, vendor `Ubuntu Developers <ubuntu-devel-discuss@lists.ubuntu.com>`)
- KEV vendor / product: TeamViewer / Desktop
- Date added to KEV: 2021-11-03
- CISA due date: 2022-05-03
- Match: `vendor+product+fuzzy` (score 100)
- CWEs: CWE-521

這個 TeamViewer 漏洞源於所有使用者安裝時使用相同的加密金鑰,讓攻擊者可以解密您儲存的無人值守存取密碼,進而遠端登入並完全控制您的電腦。您必須立即將 TeamViewer 更新至最新版本,並重新設定所有遠端存取密碼。雖然目前未被標記為勒索軟體常用手法,但此漏洞可讓攻擊者繞過登入控制直接遠端進入您的系統,就像您親自授權一樣。如果您有使用 TeamViewer 進行遠端桌面連線,這個更新非常緊急,延遲修補可能讓駭客隨時都能悄悄潛入您的電腦而不被察覺。

### **[EXPLOITED]** `CVE-2019-6340` — Drupal Core Remote Code Execution Vulnerability

- Installed: `apport-core-dump-handler` (version `2.28.1-0ubuntu3.8`, vendor `Ubuntu Developers <ubuntu-devel-discuss@lists.ubuntu.com>`)
- KEV vendor / product: Drupal / Core
- Date added to KEV: 2022-03-25
- CISA due date: 2022-04-15
- Match: `vendor+product+fuzzy` (score 100)
- CWEs: CWE-502

此 Drupal 核心漏洞因某些欄位類型未正確清理非表單來源的資料,讓攻擊者可以注入並執行任意 PHP 程式碼,完全控制您的網站伺服器並竊取資料庫內容。您應立即依 Drupal 官方指示更新至安全版本。雖然此漏洞目前未被標記為勒索軟體組織常用工具,但它允許遠端執行程式碼,攻擊者可透過精心製作的資料輸入接管整個網站。如果您有運行 Drupal 網站,請盡快完成更新,避免網站遭入侵、資料被竊或被植入惡意程式。

### **[EXPLOITED]** `CVE-2019-6340` — Drupal Core Remote Code Execution Vulnerability

- Installed: `at-spi2-core` (version `2.52.0-1build1`, vendor `Ubuntu Developers <ubuntu-devel-discuss@lists.ubuntu.com>`)
- KEV vendor / product: Drupal / Core
- Date added to KEV: 2022-03-25
- CISA due date: 2022-04-15
- Match: `vendor+product+fuzzy` (score 100)
- CWEs: CWE-502

這個 Drupal 漏洞讓攻擊者能透過未妥善驗證的資料輸入執行惡意 PHP 程式碼,進而掌控您的網站伺服器、竊取使用者資料或植入後門程式。請立即將 Drupal 更新至官方發布的修補版本。雖然目前尚未被勒索軟體組織大規模利用,但此漏洞允許遠端程式碼執行,攻擊者可在特定情況下完全控制您的網站。若您負責維護 Drupal 網站,應盡快排定時間進行更新,以防駭客利用此弱點滲透系統並造成資料外洩或服務中斷。

### **[EXPLOITED]** `CVE-2019-6340` — Drupal Core Remote Code Execution Vulnerability

- Installed: `fonts-dejavu-core` (version `2.37-8`, vendor `Ubuntu Developers <ubuntu-devel-discuss@lists.ubuntu.com>`)
- KEV vendor / product: Drupal / Core
- Date added to KEV: 2022-03-25
- CISA due date: 2022-04-15
- Match: `vendor+product+fuzzy` (score 100)
- CWEs: CWE-502

Drupal 核心的這個漏洞因資料清理不當,讓駭客可以在您的網站伺服器上執行任意 PHP 程式碼,可能導致網站被完全接管、資料庫遭竊或系統被植入惡意軟體。您需要立即按照 Drupal 維護團隊的說明安裝安全性更新。雖然此漏洞目前未被標記為勒索軟體慣用手法,但遠端程式碼執行的危險性極高,攻擊者可透過特定欄位注入惡意程式。如果您的環境中有 Drupal 網站正在運作,請優先處理這項更新,延遲修補可能讓攻擊者有機會滲透您的系統。

### **[EXPLOITED]** `CVE-2019-6340` — Drupal Core Remote Code Execution Vulnerability

- Installed: `libevent-core-2.1-7t64` (version `2.1.12-stable-9ubuntu2`, vendor `Ubuntu Developers <ubuntu-devel-discuss@lists.ubuntu.com>`)
- KEV vendor / product: Drupal / Core
- Date added to KEV: 2022-03-25
- CISA due date: 2022-04-15
- Match: `vendor+product+fuzzy` (score 100)
- CWEs: CWE-502

此 Drupal 核心漏洞允許攻擊者透過未經適當過濾的資料來源執行任意 PHP 程式碼,可能使您的網站淪為駭客跳板,或遭竊取所有敏感資訊。請盡快依照 Drupal 官方指引套用安全修補程式。雖然此漏洞目前未被勒索軟體組織廣泛運用,但它允許遠端執行程式碼的特性仍然非常危險,攻擊者一旦成功利用就能完全掌控網站。若您管理的系統中有安裝 Drupal,建議將此更新視為重要任務儘速完成,以免網站遭受入侵而影響營運或商譽。

### **[EXPLOITED]** `CVE-2019-6340` — Drupal Core Remote Code Execution Vulnerability

- Installed: `libmaven3-core-java` (version `3.8.7-2`, vendor `Ubuntu Developers <ubuntu-devel-discuss@lists.ubuntu.com>`)
- KEV vendor / product: Drupal / Core
- Date added to KEV: 2022-03-25
- CISA due date: 2022-04-15
- Match: `vendor+product+fuzzy` (score 100)
- CWEs: CWE-502

這個 Drupal 漏洞讓攻擊者能夠繞過安全機制並在您的網站伺服器執行惡意 PHP 程式碼,可能導致整個網站被控制、使用者資料外洩或被用來發動其他攻擊。您必須立即更新 Drupal 至安全版本。雖然目前未被列為勒索軟體主要攻擊手法,但此漏洞可讓駭客遠端執行任意程式,特別是針對某些欄位類型進行惡意資料注入。如果您有運營 Drupal 網站,這項更新相當重要,應儘早安排維護時間進行修補,避免系統遭駭客利用此弱點滲透。

### **[EXPLOITED]** `CVE-2019-6340` — Drupal Core Remote Code Execution Vulnerability

- Installed: `ubuntu-release-upgrader-core` (version `1:24.04.28`, vendor `Ubuntu Developers <ubuntu-devel-discuss@lists.ubuntu.com>`)
- KEV vendor / product: Drupal / Core
- Date added to KEV: 2022-03-25
- CISA due date: 2022-04-15
- Match: `vendor+product+fuzzy` (score 100)
- CWEs: CWE-502

Drupal 核心因部分欄位未正確處理外部資料,讓駭客可以注入並執行 PHP 惡意程式碼,完全掌控您的網站並可能竊取所有資料庫內容、修改網站或散播惡意軟體。請立刻依 Drupal 安全公告的步驟更新至修補版本。雖然此漏洞尚未被標記為勒索軟體組織的常用工具,但遠端程式碼執行的性質使其風險仍然很高,攻擊者可在特定條件下完全接管網站。若您負責管理 Drupal 站台,應盡快執行這項安全更新,以防止潛在的系統入侵與資料洩露事件發生。

### **[EXPLOITED]** `CVE-2019-6340` — Drupal Core Remote Code Execution Vulnerability

- Installed: `update-manager-core` (version `1:24.04.12`, vendor `Ubuntu Developers <ubuntu-devel-discuss@lists.ubuntu.com>`)
- KEV vendor / product: Drupal / Core
- Date added to KEV: 2022-03-25
- CISA due date: 2022-04-15
- Match: `vendor+product+fuzzy` (score 100)
- CWEs: CWE-502

此 Drupal 漏洞源於資料驗證不足,攻擊者可透過特定欄位注入並執行任意 PHP 程式碼,進而控制您的網站伺服器、存取敏感資料或建立管理員後門帳號。您應立即將 Drupal 更新至官方提供的安全版本。雖然目前未被勒索軟體組織大量使用,但此漏洞允許遠端程式碼執行,攻擊者一旦得手就能對網站為所欲為。如果您的系統有運行 Drupal,請將此更新列為優先事項儘快處理,避免駭客透過這個弱點入侵並造成資料外洩或服務中斷。

### **[EXPLOITED]** `CVE-2020-11023` — JQuery Cross-Site Scripting (XSS) Vulnerability

- Installed: `libjs-jquery` (version `3.6.1+dfsg+~3.5.14-1`, vendor `Ubuntu Developers <ubuntu-devel-discuss@lists.ubuntu.com>`)
- KEV vendor / product: JQuery / JQuery
- Date added to KEV: 2025-01-23
- CISA due date: 2025-02-13
- Match: `vendor+product+fuzzy` (score 100)
- CWEs: CWE-79

這個 jQuery 跨站腳本攻擊(XSS)漏洞讓駭客可以透過精心製作的惡意 HTML 標籤,在您的瀏覽器中執行未經授權的程式碼,進而竊取您的登入憑證、Cookie 或執行其他惡意操作。您應立即依照官方指示更新 jQuery 至安全版本,或若無法更新則停用相關功能。雖然此漏洞目前未被勒索軟體組織廣泛使用,但 XSS 攻擊可能導致帳號被盜用、個人資料外洩或成為釣魚攻擊的受害者。如果您的網站使用 jQuery 處理使用者輸入的內容,請盡快完成更新或套用緩解措施,以保護訪客的安全。

### **[EXPLOITED]** `CVE-2020-28949` — PEAR Archive_Tar Deserialization of Untrusted Data Vulnerability

- Installed: `tar` (version `1.35+dfsg-3build1`, vendor `Ubuntu Developers <ubuntu-devel-discuss@lists.ubuntu.com>`)
- KEV vendor / product: PEAR / Archive_Tar
- Date added to KEV: 2022-08-25
- CISA due date: 2022-09-15
- Match: `vendor+product+fuzzy` (score 100)
- CWEs: CWE-74

這個 PEAR Archive_Tar 反序列化漏洞讓攻擊者可以透過繞過大小寫檢查,在處理 TAR 壓縮檔時執行惡意程式碼,進而控制您的 PHP 網站伺服器或應用程式。您必須立即依照官方指示更新 Archive_Tar 套件及相關使用此元件的軟體(如 Drupal)。雖然目前未被勒索軟體組織大量利用,但此漏洞可讓駭客透過精心製作的壓縮檔觸發任意程式執行,特別危險於允許使用者上傳檔案的網站。如果您的 PHP 應用程式或網站使用 PEAR Archive_Tar 元件,請盡快套用安全更新,避免遭受檔案上傳攻擊而導致伺服器被入侵。

### **[EXPLOITED]** `CVE-2020-36193` — PEAR Archive_Tar Improper Link Resolution Vulnerability

- Installed: `tar` (version `1.35+dfsg-3build1`, vendor `Ubuntu Developers <ubuntu-devel-discuss@lists.ubuntu.com>`)
- KEV vendor / product: PEAR / Archive_Tar
- Date added to KEV: 2022-08-25
- CISA due date: 2022-09-15
- Match: `vendor+product+fuzzy` (score 100)
- CWEs: CWE-22, CWE-59

此 PEAR Archive_Tar 漏洞因未妥善檢查符號連結,讓攻擊者可以透過精心製作的 TAR 壓縮檔進行目錄遍歷攻擊,在您的伺服器任意位置寫入惡意檔案,包括覆蓋系統檔案或植入後門程式。您應立即更新 Archive_Tar 套件及使用此元件的軟體(如 Drupal、某些 Red Hat Linux 套件)至安全版本。雖然此漏洞目前未被勒索軟體組織標記為常用手法,但任意檔案寫入的危險性極高,攻擊者可透過上傳惡意壓縮檔完全控制您的網站或伺服器。如果您的 PHP 應用程式處理使用者上傳的 TAR 檔案,請立即套用更新,避免駭客利用此弱點破壞系統完整性或竊取敏感資料。

### **[EXPLOITED]** `CVE-2021-3156` — Sudo Heap-Based Buffer Overflow Vulnerability

- Installed: `sudo` (version `1.9.15p5-3ubuntu5.24.04.2`, vendor `Ubuntu Developers <ubuntu-devel-discuss@lists.ubuntu.com>`)
- KEV vendor / product: Sudo / Sudo
- Date added to KEV: 2022-04-06
- CISA due date: 2022-04-27
- Match: `vendor+product+fuzzy` (score 100)
- CWEs: CWE-122, CWE-193

這個 Sudo「Baron Samedit」漏洞讓任何本機使用者(包括無特權的帳號)都能透過堆積緩衝區溢位錯誤取得最高管理員(root)權限,完全控制整個系統並可執行任何操作。您必須立即透過系統更新機制安裝 Sudo 的安全修補版本。雖然此漏洞目前未被標記為勒索軟體組織常用手法,但它允許任何本機使用者提升至 root 權限,對多使用者系統或被植入惡意程式的系統極度危險。這個更新非常重要且應立即處理,特別是如果您的 Linux 系統有多位使用者或可能被入侵,延遲修補將讓攻擊者輕易取得系統最高控制權。

### **[EXPLOITED]** `CVE-2023-20867` — VMware Tools Authentication Bypass Vulnerability

- Installed: `libpng-tools` (version `1.6.43-5ubuntu0.5`, vendor `Ubuntu Developers <ubuntu-devel-discuss@lists.ubuntu.com>`)
- KEV vendor / product: VMware / Tools
- Date added to KEV: 2023-06-23
- CISA due date: 2023-07-14
- Match: `vendor+product+fuzzy` (score 100)
- CWEs: CWE-287

這個 VMware Tools 漏洞讓已被入侵的 ESXi 主機能夠繞過身份驗證機制,強制 VMware Tools 無法正確驗證主機對客體虛擬機的操作,進而竊取虛擬機內的敏感資料或修改其內容。您應立即依照 VMware 官方指示更新 VMware Tools 至安全版本。雖然此漏洞目前未被勒索軟體組織廣泛利用,且攻擊者必須先取得 ESXi 主機的 root 權限才能利用,但一旦 ESXi 被入侵,這個漏洞將讓攻擊者進一步滲透所有客體虛擬機。如果您在虛擬化環境中運行虛擬機,請盡快更新 VMware Tools,特別是在共享或雲端主機環境中,以維護虛擬機的安全隔離性。

### **[EXPLOITED]** `CVE-2023-20867` — VMware Tools Authentication Bypass Vulnerability

- Installed: `linux-tools-6.8.0-110` (version `6.8.0-110.110`, vendor `Ubuntu Kernel Team <kernel-team@lists.ubuntu.com>`)
- KEV vendor / product: VMware / Tools
- Date added to KEV: 2023-06-23
- CISA due date: 2023-07-14
- Match: `vendor+product+fuzzy` (score 100)
- CWEs: CWE-287

此 VMware Tools 驗證繞過漏洞允許已遭攻陷的 ESXi 虛擬化主機跳過身份驗證,直接對客體虛擬機執行未授權操作,可能導致虛擬機內的資料被竊取或遭到竄改。請立即依 VMware 官方說明將 VMware Tools 更新至修補版本。雖然此漏洞目前未被勒索軟體組織標記為常用手法,且需要攻擊者先擁有 ESXi 主機的 root 權限,但在虛擬化環境中,一旦主機層被入侵,這個漏洞將使所有虛擬機的安全防線失效。如果您使用 VMware 虛擬機,特別是在多租戶或雲端環境,應盡快完成更新以確保虛擬機與主機之間的信任機制正常運作。

### **[EXPLOITED]** `CVE-2023-20867` — VMware Tools Authentication Bypass Vulnerability

- Installed: `linux-tools-6.8.0-110-generic` (version `6.8.0-110.110`, vendor `Ubuntu Kernel Team <kernel-team@lists.ubuntu.com>`)
- KEV vendor / product: VMware / Tools
- Date added to KEV: 2023-06-23
- CISA due date: 2023-07-14
- Match: `vendor+product+fuzzy` (score 100)
- CWEs: CWE-287

VMware Tools 的這個漏洞讓被完全控制的 ESXi 虛擬化主機能繞過 vgauth 模組的驗證,強制對客體虛擬機執行惡意操作,威脅虛擬機內資料的機密性與完整性。您需要立刻按照 VMware 提供的指示更新 VMware Tools。雖然此漏洞尚未被勒索軟體組織大量使用,且攻擊者必須先取得 ESXi 主機的最高權限,但在企業虛擬化環境中,主機一旦淪陷將連帶影響所有虛擬機的安全。若您在 VMware 環境中運行虛擬機,請優先處理此更新,以維持主機與虛擬機之間應有的安全隔離與信任邊界。

### **[EXPLOITED]** `CVE-2023-20867` — VMware Tools Authentication Bypass Vulnerability

- Installed: `linux-tools-common` (version `6.8.0-110.110`, vendor `Ubuntu Kernel Team <kernel-team@lists.ubuntu.com>`)
- KEV vendor / product: VMware / Tools
- Date added to KEV: 2023-06-23
- CISA due date: 2023-07-14
- Match: `vendor+product+fuzzy` (score 100)
- CWEs: CWE-287

這個 VMware Tools 漏洞使已被入侵的 ESXi 主機可以強制 VMware Tools 無法正確驗證主機發起的操作,進而對虛擬機內的資料進行未授權存取或修改。您應盡快依 VMware 官方公告更新 VMware Tools 至安全版本。雖然攻擊者必須先擁有 ESXi 主機的 root 存取權才能利用此漏洞,且目前未被勒索軟體組織廣泛運用,但在虛擬化架構中,此漏洞將破壞主機與虛擬機之間的信任關係。如果您使用 VMware 虛擬化平台,建議儘早完成更新,特別是在共享基礎設施環境中,以防止主機層攻擊擴散至所有虛擬機。

### **[EXPLOITED]** `CVE-2023-20867` — VMware Tools Authentication Bypass Vulnerability

- Installed: `linux-tools-generic` (version `6.8.0-110.110`, vendor `Ubuntu Kernel Team <kernel-team@lists.ubuntu.com>`)
- KEV vendor / product: VMware / Tools
- Date added to KEV: 2023-06-23
- CISA due date: 2023-07-14
- Match: `vendor+product+fuzzy` (score 100)
- CWEs: CWE-287

此 VMware Tools 驗證漏洞允許已遭攻陷的 ESXi 虛擬化主機繞過身份驗證,對客體虛擬機執行惡意的主機對客體操作,危及虛擬機的資料安全與系統完整性。請立即更新 VMware Tools 至 VMware 官方發布的安全修補版本。雖然利用此漏洞的前提是攻擊者已擁有 ESXi 主機的完整控制權,且目前未被勒索軟體組織標記為主要工具,但在虛擬化環境中這代表單一主機被入侵將波及所有虛擬機。若您在 VMware 平台上運行虛擬機,請將此更新列為重要事項儘快處理,以確保虛擬機層級的安全隔離機制能正常發揮作用。

### **[EXPLOITED]** `CVE-2023-20867` — VMware Tools Authentication Bypass Vulnerability

- Installed: `packagekit-tools` (version `1.2.8-2ubuntu1.4`, vendor `Ubuntu Developers <ubuntu-devel-discuss@lists.ubuntu.com>`)
- KEV vendor / product: VMware / Tools
- Date added to KEV: 2023-06-23
- CISA due date: 2023-07-14
- Match: `vendor+product+fuzzy` (score 100)
- CWEs: CWE-287

VMware Tools 的這個驗證繞過漏洞讓完全掌控 ESXi 主機的攻擊者能強制 vgauth 模組驗證失效,從而對客體虛擬機進行未經授權的操作,包括竊取機密資料或篡改系統設定。您必須依照 VMware 官方指示立即更新 VMware Tools。雖然此漏洞需要攻擊者先取得 ESXi 主機 root 權限且目前未被勒索軟體大量利用,但虛擬化環境的特性使得主機層入侵會直接威脅所有虛擬機的安全性。如果您的系統運行於 VMware 虛擬機中,應盡快套用更新,避免在主機遭受攻擊時失去虛擬機應有的安全防護。

### **[EXPLOITED]** `CVE-2023-20867` — VMware Tools Authentication Bypass Vulnerability

- Installed: `squashfs-tools` (version `1:4.6.1-1build1`, vendor `Ubuntu Developers <ubuntu-devel-discuss@lists.ubuntu.com>`)
- KEV vendor / product: VMware / Tools
- Date added to KEV: 2023-06-23
- CISA due date: 2023-07-14
- Match: `vendor+product+fuzzy` (score 100)
- CWEs: CWE-287

這個 VMware Tools 漏洞讓已被完全控制的 ESXi 虛擬化主機能繞過驗證機制,對客體虛擬機執行惡意操作並影響其資料機密性與完整性。請立即按 VMware 官方公告的步驟更新 VMware Tools。雖然此漏洞的利用前提是攻擊者已取得 ESXi 主機最高權限,且尚未被勒索軟體組織廣泛採用,但在虛擬化基礎設施中,主機一旦淪陷將使所有虛擬機的安全邊界失效。若您在 VMware 環境中運行業務系統,請儘早完成這項更新,特別是在企業或雲端環境中,以確保虛擬機層級的隔離與保護機制正常運作。

### **[EXPLOITED]** `CVE-2024-23692` — Rejetto HTTP File Server Improper Neutralization of Special Elements Used in a Template Engine Vulnerability

- Installed: `file` (version `1:5.45-3build1`, vendor `Ubuntu Developers <ubuntu-devel-discuss@lists.ubuntu.com>`)
- KEV vendor / product: Rejetto / HTTP File Server
- Date added to KEV: 2024-07-09
- CISA due date: 2024-07-30
- Match: `vendor+product+fuzzy` (score 100)
- CWEs: CWE-1336

這個 Rejetto HTTP File Server 漏洞讓遠端攻擊者無需任何帳號密碼,僅透過發送精心製作的 HTTP 請求就能在您的伺服器上執行任意系統指令,完全控制整台電腦。您必須立即依照官方指示套用緩解措施,若無可用的修補方案則應停止使用此軟體。雖然此漏洞目前未被勒索軟體組織廣泛利用,但它允許未經驗證的遠端程式碼執行,任何能連上您伺服器的人都可能發動攻擊,危險性極高。如果您正在使用 Rejetto HFS 分享檔案,請立即停止服務並套用更新,或改用其他更安全的檔案分享方案,避免系統遭到入侵。

### **[EXPLOITED]** `CVE-2025-11953` — React Native Community CLI OS Command Injection Vulnerability

- Installed: `libcommons-cli-java` (version `1.6.0-1`, vendor `Ubuntu Developers <ubuntu-devel-discuss@lists.ubuntu.com>`)
- KEV vendor / product: React Native Community / CLI
- Date added to KEV: 2026-02-05
- CISA due date: 2026-02-26
- Match: `vendor+product+fuzzy` (score 100)
- CWEs: CWE-78

這個 React Native Community CLI 漏洞讓未經驗證的網路攻擊者可以向 Metro 開發伺服器發送 POST 請求,透過暴露的脆弱端點執行任意可執行檔,在 Windows 系統上甚至能以完全控制的參數執行任何 Shell 指令。您必須立即依照官方指示套用緩解措施,遵循相關雲端服務安全指引,或若無可用修補方案則停止使用該產品。雖然此漏洞目前未被勒索軟體組織標記為常用手法,但它允許遠端未授權的指令注入攻擊,攻擊者可透過網路直接控制您的開發環境或系統。如果您正在使用 React Native 進行應用程式開發,請立即檢查並更新 CLI 工具,或暫時關閉 Metro 伺服器對外連線,避免開發環境遭到入侵而危及整個專案安全。

### **[EXPLOITED]** `CVE-2025-32463` — Sudo Inclusion of Functionality from Untrusted Control Sphere Vulnerability

- Installed: `sudo` (version `1.9.15p5-3ubuntu5.24.04.2`, vendor `Ubuntu Developers <ubuntu-devel-discuss@lists.ubuntu.com>`)
- KEV vendor / product: Sudo / Sudo
- Date added to KEV: 2025-09-29
- CISA due date: 2025-10-20
- Match: `vendor+product+fuzzy` (score 100)
- CWEs: CWE-829

這個 Sudo 漏洞讓本機攻擊者可以利用 sudo 的 -R (--chroot) 選項,即使未被列入 sudoers 授權清單中,也能以 root 最高權限執行任意指令,完全掌控整個系統。您必須立即依照官方指示套用緩解措施,遵循相關雲端服務安全指引,或若無可用修補方案則停用該功能。雖然此漏洞目前未被勒索軟體組織廣泛利用,但它允許本機使用者繞過 sudoers 設定提升至 root 權限,在多使用者環境或已被植入惡意程式的系統中極度危險。請立即更新 Sudo 至安全版本或套用限制措施,特別是在伺服器或共享系統環境中,避免未授權的權限提升導致系統完全失守。

### **[EXPLOITED]** `CVE-2025-48384` — Git Link Following Vulnerability

- Installed: `git` (version `1:2.43.0-1ubuntu7.3`, vendor `Ubuntu Developers <ubuntu-devel-discuss@lists.ubuntu.com>`)
- KEV vendor / product: Git / Git
- Date added to KEV: 2025-08-25
- CISA due date: 2025-09-15
- Match: `vendor+product+fuzzy` (score 100)
- CWEs: CWE-59, CWE-436

這個 Git 漏洞源於 Git 對設定檔中換行字元的處理不一致,讓攻擊者可以透過符號連結攻擊手法,可能導致任意檔案被讀取、覆寫或執行未預期的指令。您應立即依照官方指示套用緩解措施或更新 Git 至安全版本,若無可用修補方案則需遵循相關安全指引。雖然此漏洞目前未被勒索軟體組織廣泛利用,但攻擊者可能透過惡意的 Git 儲存庫或設定檔觸發此弱點,在您執行 Git 操作時危害系統安全。如果您經常使用 Git 進行版本控制或從網路複製儲存庫,請盡快更新 Git 並謹慎處理來自不明來源的專案,避免遭受潛在的檔案系統攻擊。

### **[EXPLOITED]** `CVE-2025-48384` — Git Link Following Vulnerability

- Installed: `git-man` (version `1:2.43.0-1ubuntu7.3`, vendor `Ubuntu Developers <ubuntu-devel-discuss@lists.ubuntu.com>`)
- KEV vendor / product: Git / Git
- Date added to KEV: 2025-08-25
- CISA due date: 2025-09-15
- Match: `vendor+product+fuzzy` (score 100)
- CWEs: CWE-59, CWE-436

此 Git 漏洞因設定檔中回車字元的處理方式不一致,可能被攻擊者利用進行符號連結攻擊,進而讀取敏感檔案、修改系統檔案或執行惡意操作。請立即依官方指引更新 Git 至修補版本或套用緩解措施,若無可用更新則應遵循相關雲端服務安全建議。雖然此漏洞尚未被勒索軟體組織大量使用,但攻擊者可透過精心製作的 Git 設定檔或惡意儲存庫觸發此弱點,當您 clone 或操作這些專案時可能遭受攻擊。如果您日常使用 Git 管理程式碼或從 GitHub 等平台下載專案,請優先處理此更新,並避免執行來路不明的 Git 儲存庫操作。

### **[EXPLOITED]** `CVE-2025-48543` — Android Runtime Use-After-Free Vulnerability

- Installed: `libpam-runtime` (version `1.5.3-5ubuntu5.5`, vendor `Ubuntu Developers <ubuntu-devel-discuss@lists.ubuntu.com>`)
- KEV vendor / product: Android / Runtime
- Date added to KEV: 2025-09-04
- CISA due date: 2025-09-25
- Match: `vendor+product+fuzzy` (score 100)

這個 Android Runtime 釋放後使用(use-after-free)漏洞可能讓攻擊者逃脫 Chrome 瀏覽器的沙箱保護機制,進而提升至本機系統權限,完全控制您的 Android 裝置或系統。您應立即依照官方指示套用安全更新或緩解措施,遵循相關雲端服務安全指引,若無可用修補方案則需停用受影響功能。雖然此漏洞目前未被勒索軟體組織廣泛利用,但它允許從瀏覽器沙箱逃逸並提升權限,攻擊者可能透過惡意網頁觸發此弱點。如果您使用 Android 裝置或 Chrome 瀏覽器,請盡快檢查並安裝系統更新,特別是經常瀏覽網頁或下載應用程式的使用者,以避免遭受沙箱逃逸攻擊而導致裝置被完全控制。

### **[EXPLOITED]** `CVE-2025-48543` — Android Runtime Use-After-Free Vulnerability

- Installed: `uuid-runtime` (version `2.39.3-9ubuntu6.5`, vendor `Ubuntu Developers <ubuntu-devel-discuss@lists.ubuntu.com>`)
- KEV vendor / product: Android / Runtime
- Date added to KEV: 2025-09-04
- CISA due date: 2025-09-25
- Match: `vendor+product+fuzzy` (score 100)

此 Android Runtime 漏洞是一個釋放後使用的記憶體安全問題,可能讓攻擊者突破 Chrome 瀏覽器的沙箱隔離機制,取得本機系統的提升權限並控制您的裝置。請立即依官方指示安裝安全更新或套用緩解措施,遵循適用的雲端服務安全建議,若無修補方案則應停用相關功能。雖然此漏洞尚未被勒索軟體組織標記為常用手法,但沙箱逃逸配合權限提升可讓攻擊者從受限的瀏覽器環境完全掌控整個系統。如果您使用 Android 手機或平板,或在電腦上使用 Chrome 瀏覽器,請優先檢查並套用系統更新,避免在瀏覽惡意網頁時遭受沙箱突破攻擊。

### **[EXPLOITED]** `CVE-2025-48543` — Android Runtime Use-After-Free Vulnerability

- Installed: `vim-runtime` (version `2:9.1.0016-1ubuntu7.11`, vendor `Ubuntu Developers <ubuntu-devel-discuss@lists.ubuntu.com>`)
- KEV vendor / product: Android / Runtime
- Date added to KEV: 2025-09-04
- CISA due date: 2025-09-25
- Match: `vendor+product+fuzzy` (score 100)

這個 Android Runtime 釋放後使用漏洞讓攻擊者能夠逃離 Chrome 瀏覽器的安全沙箱,進一步提升至系統層級權限,完全接管您的 Android 裝置或電腦。您必須立即按照官方說明套用安全修補程式或緩解措施,遵循相關安全指引,若無可用更新則需停用受影響的功能。雖然目前未被勒索軟體組織大規模利用,但此漏洞結合沙箱逃逸與權限提升,攻擊者可能透過瀏覽惡意網站就突破所有防線。如果您使用 Android 裝置、Chrome 或 Chromium 瀏覽器,請將系統更新列為最優先事項立即執行,特別是經常上網的使用者,以防止瀏覽器層級的攻擊擴散至整個系統。

### **[EXPLOITED]** `CVE-2026-3502` — TrueConf Client Download of Code Without Integrity Check Vulnerability

- Installed: `gpg-wks-client` (version `2.4.4-2ubuntu17.4`, vendor `Ubuntu Developers <ubuntu-devel-discuss@lists.ubuntu.com>`)
- KEV vendor / product: TrueConf / Client
- Date added to KEV: 2026-04-02
- CISA due date: 2026-04-16
- Match: `vendor+product+fuzzy` (score 100)
- CWEs: CWE-494

這個 TrueConf Client 漏洞因更新機制未檢查程式碼完整性,讓能夠影響更新傳遞路徑的攻擊者可以替換成惡意的更新檔案,當更新程式執行或安裝時就會以系統權限執行任意惡意程式碼。您應立即依照官方指示套用緩解措施或更新至安全版本,遵循相關雲端服務安全建議,若無可用修補方案則應停止使用該軟體。雖然此漏洞目前未被勒索軟體組織廣泛利用,但攻擊者可透過中間人攻擊或 DNS 劫持等方式在更新過程中植入惡意程式,危險性不容小覷。如果您使用 TrueConf 進行視訊會議,請盡快檢查並套用安全更新,或暫時改用其他經過驗證的通訊軟體,避免在自動更新時遭到惡意程式植入。

### **[EXPLOITED]** `CVE-2026-3502` — TrueConf Client Download of Code Without Integrity Check Vulnerability

- Installed: `landscape-client` (version `24.02-0ubuntu5.7`, vendor `Ubuntu Developers <ubuntu-devel-discuss@lists.ubuntu.com>`)
- KEV vendor / product: TrueConf / Client
- Date added to KEV: 2026-04-02
- CISA due date: 2026-04-16
- Match: `vendor+product+fuzzy` (score 100)
- CWEs: CWE-494

此 TrueConf Client 漏洞因缺乏更新檔案完整性驗證,讓攻擊者若能控制更新傳輸路徑,就可注入經過竄改的惡意更新檔,一旦更新程式執行就會以使用者或系統權限執行任意程式碼。請立即依官方指引套用安全修補或緩解措施,遵循適用的雲端服務安全建議,若無可用更新則需停止使用該產品。雖然此漏洞尚未被勒索軟體組織標記為常用手法,但攻擊者可透過網路劫持或偽造更新伺服器等方式在自動更新時植入惡意軟體,風險相當高。如果您安裝了 TrueConf 視訊會議軟體,請盡快更新至安全版本並確認連線至官方更新伺服器,或暫時停用自動更新功能,避免遭受供應鏈攻擊而導致系統淪陷。

### **[EXPLOITED]** `CVE-2026-3502` — TrueConf Client Download of Code Without Integrity Check Vulnerability

- Installed: `openssh-client` (version `1:9.6p1-3ubuntu13.15`, vendor `Ubuntu Developers <ubuntu-devel-discuss@lists.ubuntu.com>`)
- KEV vendor / product: TrueConf / Client
- Date added to KEV: 2026-04-02
- CISA due date: 2026-04-16
- Match: `vendor+product+fuzzy` (score 100)
- CWEs: CWE-494

TrueConf Client 的這個漏洞因未對下載的更新程式碼進行完整性檢查,讓能夠干預更新傳遞路徑的攻擊者可以替換成惡意更新封包,導致更新程式以系統或使用者權限執行任意惡意程式。您必須立即依照官方說明套用安全更新或緩解措施,遵循相關雲端服務安全指引,若無修補方案則應停止使用該軟體。雖然目前未被勒索軟體組織大量利用,但此漏洞讓攻擊者可在更新過程中進行供應鏈攻擊,透過網路中間人或 DNS 污染等手法植入惡意程式。如果您使用 TrueConf 進行遠端會議,請優先處理此安全更新,並確保只從官方來源下載更新,或考慮暫時改用其他具備更新驗證機制的視訊軟體。

### **[EXPLOITED]** `CVE-2026-3502` — TrueConf Client Download of Code Without Integrity Check Vulnerability

- Installed: `ubuntu-pro-client` (version `37.1ubuntu0~24.04`, vendor `Ubuntu Developers <ubuntu-devel-discuss@lists.ubuntu.com>`)
- KEV vendor / product: TrueConf / Client
- Date added to KEV: 2026-04-02
- CISA due date: 2026-04-16
- Match: `vendor+product+fuzzy` (score 100)
- CWEs: CWE-494

這個 TrueConf Client 漏洞因更新機制缺乏程式碼完整性驗證,攻擊者若能影響更新下載路徑,就可以注入經過竄改的惡意更新,當更新程式執行時將以使用者或系統權限運行任意程式碼。請立即按照官方指示更新至安全版本或套用緩解措施,遵循適用的雲端服務安全建議,若無可用修補則應停止使用。雖然此漏洞尚未被勒索軟體組織廣泛運用,但它允許攻擊者透過劫持更新傳輸進行供應鏈攻擊,在自動更新過程中植入惡意軟體而不被察覺。如果您有安裝 TrueConf 視訊會議軟體,請盡快確認並套用安全更新,確保更新來源的真實性,或暫時停用自動更新功能直到修補完成為止。

### **[EXPLOITED]** `CVE-2026-3502` — TrueConf Client Download of Code Without Integrity Check Vulnerability

- Installed: `ubuntu-pro-client-l10n` (version `37.1ubuntu0~24.04`, vendor `Ubuntu Developers <ubuntu-devel-discuss@lists.ubuntu.com>`)
- KEV vendor / product: TrueConf / Client
- Date added to KEV: 2026-04-02
- CISA due date: 2026-04-16
- Match: `vendor+product+fuzzy` (score 100)
- CWEs: CWE-494

此 TrueConf Client 漏洞源於更新下載過程未驗證程式碼完整性,使得能夠控制更新傳遞路徑的攻擊者可以替換成惡意更新檔案,一旦被安裝執行就會以更新程式的權限運行任意惡意程式碼。您應立即依官方指引套用安全更新或緩解方案,遵循相關雲端服務安全建議,若無可用修補則需停止使用該軟體。雖然目前未被勒索軟體組織標記為主要攻擊工具,但此漏洞讓攻擊者可透過網路攔截或偽造更新伺服器等方式在更新時植入惡意程式,屬於供應鏈攻擊手法。如果您使用 TrueConf 進行視訊通訊,請優先檢查並安裝安全更新,並確保網路連線的安全性,或考慮暫時改用其他具備數位簽章驗證的通訊軟體。

### **[EXPLOITED]** `CVE-2021-3560` — Red Hat Polkit Incorrect Authorization Vulnerability

- Installed: `polkitd` (version `124-2ubuntu1.24.04.3`, vendor `Ubuntu Developers <ubuntu-devel-discuss@lists.ubuntu.com>`)
- KEV vendor / product: Red Hat / Polkit
- Date added to KEV: 2023-05-12
- CISA due date: 2023-06-02
- Match: `vendor+product+fuzzy` (score 92)
- CWEs: CWE-863

這個 Polkit 漏洞讓本機使用者可以透過繞過 D-Bus 請求的憑證檢查,從普通使用者權限提升至系統管理員(root)權限,完全控制整個系統並執行任何特權操作。您必須立即透過系統更新機制安裝 Polkit 的安全修補程式。雖然此漏洞目前未被勒索軟體組織廣泛利用,但它允許本機攻擊者輕易提升權限,在多使用者環境或已被植入惡意程式的系統中極度危險。請將此更新列為高優先事項立即執行,特別是伺服器或共享電腦環境,避免未授權的使用者或惡意程式利用此弱點取得系統最高控制權並造成嚴重破壞。

### **[EXPLOITED]** `CVE-2021-4034` — Red Hat Polkit Out-of-Bounds Read and Write Vulnerability

- Installed: `polkitd` (version `124-2ubuntu1.24.04.3`, vendor `Ubuntu Developers <ubuntu-devel-discuss@lists.ubuntu.com>`)
- KEV vendor / product: Red Hat / Polkit
- Date added to KEV: 2022-06-27
- CISA due date: 2022-07-18
- Match: `vendor+product+fuzzy` (score 92)
- CWEs: CWE-787

這個 Polkit「PwnKit」漏洞存在於 pkexec 工具中,讓任何本機使用者都能透過越界讀寫記憶體錯誤取得系統管理員權限,完全掌控電腦並執行任何特權指令。您應立即透過系統更新安裝 Polkit 的安全修補版本。雖然此漏洞目前未被勒索軟體組織標記為常用手法,但它允許本機使用者輕易提升至 root 權限,對多使用者系統或已被入侵的系統威脅極大。這個更新非常重要且應立即處理,特別是 Linux 伺服器或共享電腦環境,延遲修補將讓攻擊者或惡意程式能夠瞬間取得系統最高控制權並為所欲為。

## How to read this report

Every entry above maps to a vulnerability that **CISA has confirmed is being exploited in the wild**. A match here means you have software from the same product family — it does *not* prove your specific version is vulnerable. Verify each finding against the vendor's advisory page before acting. Ransomware-linked entries should be patched first.
