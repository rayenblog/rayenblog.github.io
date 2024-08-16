---
title: "Microsoft: August 2024 Security Updates"
date: "2024-04-14 22:30:00 +0100"
tags: [security]
categories: [microsoft, pathces, security, security vulnerability, windows, kernel, office, azure]
---
[![StandWithPalestine](https://raw.githubusercontent.com/Safouene1/support-palestine-banner/master/StandWithPalestine.svg)](https://techforpalestine.org/learn-more)

In August 2024, Microsoft released a significant security update addressing a total of **90 Common Vulnerabilities and Exposures (CVEs)**. This comprehensive update spans various Microsoft products, including Windows, Azure, Office, and more. Below is an in-depth look at the key details of these vulnerabilities.

## Key Highlights

- **Total CVEs:** 90
- **Critical Vulnerabilities:** Several critical vulnerabilities with CVSS scores as high as 9.8.
- **Affected Products:** Windows, Azure, Microsoft Office, .NET, and more.

## Vulnerability Breakdown

| Tag                                    | CVE            | Base Score | CVSS Vector                                                                                   | Exploitability        | FAQs? | Workarounds? | Mitigations? |
|----------------------------------------|-----------------|------------|-----------------------------------------------------------------------------------------------|-----------------------|-------|--------------|--------------|
| Windows Secure Kernel Mode             | CVE-2024-21302  | 6.7        | CVSS:3.1/AV:L/AC:L/PR:H/UI:N/S:U/C:H/I:H/A:H/E:U/RL:U/RC:C                                  | Exploitation Less Likely | Yes   | No           | No           |
| Windows Kerberos                       | CVE-2024-29995  | 8.1        | CVSS:3.1/AV:N/AC:H/PR:N/UI:N/S:U/C:H/I:H/A:H/E:U/RL:O/RC:C                                  | Exploitation Less Likely | Yes   | No           | No           |
| Microsoft Windows DNS                  | CVE-2024-37968  | 7.5        | CVSS:3.1/AV:N/AC:L/PR:N/UI:N/S:U/C:H/I:N/A:N/E:P/RL:O/RC:C                                  | Exploitation Less Likely | No    | No           | No           |
| Windows TCP/IP                         | CVE-2024-38063  | 9.8        | CVSS:3.1/AV:N/AC:L/PR:N/UI:N/S:U/C:H/I:H/A:H/E:U/RL:O/RC:C                                  | Exploitation More Likely  | Yes   | No           | Yes          |
| Microsoft Office                       | CVE-2024-38084  | 7.8        | CVSS:3.1/AV:L/AC:L/PR:L/UI:N/S:U/C:H/I:H/A:H/E:U/RL:O/RC:C                                  | Exploitation Less Likely | Yes   | No           | No           |
| Azure Connected Machine Agent          | CVE-2024-38098  | 7.8        | CVSS:3.1/AV:L/AC:L/PR:L/UI:N/S:U/C:H/I:H/A:H/E:U/RL:O/RC:C                                  | Exploitation Unlikely     | Yes   | No           | No           |
| Windows Kernel                         | CVE-2024-38106  | 7.0        | CVSS:3.1/AV:L/AC:H/PR:L/UI:N/S:U/C:H/I:H/A:H/E:F/RL:O/RC:C                                  | Exploitation Detected      | Yes   | No           | No           |
| Windows Power Dependency Coordinator    | CVE-2024-38107  | 7.8        | CVSS:3.1/AV:L/AC:L/PR:L/UI:N/S:U/C:H/I:H/A:H/E:F/RL:O/RC:C                                  | Exploitation Detected      | Yes   | No           | No           |
| Azure Stack                            | CVE-2024-38108  | 9.3        | CVSS:3.1/AV:N/AC:L/PR:N/UI:R/S:C/C:H/I:H/A:N/E:U/RL:O/RC:C                                  | Exploitation Less Likely | Yes   | No           | No           |
| Azure Health Bot                       | CVE-2024-38109  | 9.1        | CVSS:3.1/AV:N/AC:L/PR:N/UI:N/S:U/C:H/I:N/A:H/E:U/RL:O/RC:C                                  | Exploitation Less Likely | Yes   | No           | No           |
| Windows IP Routing Management Snapin    | CVE-2024-38114  | 8.8        | CVSS:3.1/AV:N/AC:L/PR:N/UI:R/S:U/C:H/I:H/A:H/E:U/RL:O/RC:C                                  | Exploitation Less Likely | Yes   | No           | No           |
| Windows IP Routing Management Snapin    | CVE-2024-38115  | 8.8        | CVSS:3.1/AV:N/AC:L/PR:N/UI:R/S:U/C:H/I:H/A:H/E:U/RL:O/RC:C                                  | Exploitation Less Likely | Yes   | No           | No           |
| Windows IP Routing Management Snapin    | CVE-2024-38116  | 8.8        | CVSS:3.1/AV:N/AC:L/PR:L/UI:N/S:U/C:H/I:H/A:H/E:U/RL:O/RC:C                                  | Exploitation Less Likely | Yes   | No           | No           |
| Windows NTFS                           | CVE-2024-38117  | 7.8        | CVSS:3.1/AV:L/AC:L/PR:L/UI:N/S:U/C:H/I:H/A:H/E:U/RL:O/RC:C                                  | Exploitation Less Likely | Yes   | No           | No           |
| Microsoft Local Security Authority Server (lsasrv) | CVE-2024-38118  | 5.5        | CVSS:3.1/AV:L/AC:L/PR:L/UI:N/S:U/C:H/I:N/A:N/E:U/RL:O/RC:C                                  | Exploitation Less Likely | Yes   | No           | No           |
| Windows Routing and Remote Access Service (RRAS) | CVE-2024-38120  | 8.8        | CVSS:3.1/AV:N/AC:L/PR:N/UI:R/S:U/C:H/I:H/A:H/E:U/RL:O/RC:C                                  | Exploitation Less Likely | Yes   | No           | No           |
| Windows Routing and Remote Access Service (RRAS) | CVE-2024-38121  | 8.8        | CVSS:3.1/AV:N/AC:L/PR:N/UI:R/S:U/C:H/I:H/A:H/E:U/RL:O/RC:C                                  | Exploitation Less Likely | Yes   | No           | No           |
| Microsoft Local Security Authority Server (lsasrv) | CVE-2024-38122  | 5.5        | CVSS:3.1/AV:L/AC:L/PR:L/UI:N/S:U/C:H/I:N/A:N/E:U/RL:O/RC:C                                  | Exploitation Less Likely | Yes   | No           | No           |
| Microsoft Bluetooth Driver             | CVE-2024-38123  | 4.4        | CVSS:3.1/AV:L/AC:L/PR:H/UI:N/S:U/C:H/I:N/A:N/E:U/RL:O/RC:C                                  | Exploitation Less Likely | Yes   | No           | No           |
| Microsoft Streaming Service            | CVE-2024-38125  | 7.8        | CVSS:3.1/AV:L/AC:L/PR:L/UI:N/S:U/C:H/I:H/A:H/E:U/RL:O/RC:C                                  | Exploitation More Likely  | Yes   | No           | No           |
| Windows Network Address Translation (NAT) | CVE-2024-38126  | 7.5        | CVSS:3.1/AV:N/AC:L/PR:N/UI:N/S:U/C:N/I:N/A:H/E:U/RL:O/RC:C                                  | Exploitation Less Likely | Yes   | No           | No           |
| Windows Kernel                         | CVE-2024-38127  | 7.8        | CVSS:3.1/AV:L/AC:L/PR:L/UI:N/S:U/C:H/I:H/A:H/E:U/RL:O/RC:C                                  | Exploitation Less Likely | Yes   | No           | No           |
| Windows Routing and Remote Access Service (RRAS) | CVE-2024-38128  | 8.8        | CVSS:3.1/AV:N/AC:L/PR:N/UI:R/S:U/C:H/I:H/A:H/E:U/RL:O/RC:C                                  | Exploitation Less Likely | Yes   | No           | No           |
| Windows Routing and Remote Access Service (RRAS) | CVE-2024-38130  | 8.8        | CVSS:3.1/AV:N/AC:L/PR:N/UI:R/S:U/C:H/I:H/A:H/E:U/RL:O/RC:C                                  | Exploitation Less Likely | Yes   | No           | No           |
| Windows Clipboard Virtual Channel Extension | CVE-2024-38131  | 8.8        | CVSS:3.1/AV:N/AC:L/PR:N/UI:R/S:U/C:H/I:H/A:H/E:U/RL:O/RC:C                                  | Exploitation Less Likely | Yes   | No           | No           |
| Windows Network Address Translation (NAT) | CVE-2024-38132  | 7.5        | CVSS:3.1/AV:N/AC:L/PR:N/UI:N/S:U/C:N/I:N/A:H/E:U/RL:O/RC:C                                  | Exploitation Less Likely | Yes   | No           | No           |
| Windows Local Security Authority Server (lsasrv) | CVE-2024-38134  | 5.5        | CVSS:3.1/AV:L/AC:L/PR:L/UI:N/S:U/C:H/I:N/A:N/E:U/RL:O/RC:C                                  | Exploitation Less Likely | Yes   | No           | No           |
| Windows Routing and Remote Access Service (RRAS) | CVE-2024-38135  | 8.8        | CVSS:3.1/AV:N/AC:L/PR:N/UI:R/S:U/C:H/I:H/A:H/E:U/RL:O/RC:C                                  | Exploitation Less Likely | Yes   | No           | No           |
| Microsoft Windows Server Remote Desktop Services | CVE-2024-38136  | 9.8        | CVSS:3.1/AV:N/AC:L/PR:N/UI:R/S:U/C:H/I:H/A:H/E:U/RL:O/RC:C                                  | Exploitation More Likely  | Yes   | No           | Yes          |


## Notable CVEs

### CVE-2024-38063: Windows TCP/IP Vulnerability
- **CVSS Score:** 9.8
- **Description:** A critical vulnerability in the Windows TCP/IP stack could allow remote attackers to execute arbitrary code on affected systems without user interaction. This vulnerability is rated as "Exploitation More Likely," emphasizing the importance of immediate patching.

### CVE-2024-38108: Azure Stack Vulnerability
- **CVSS Score:** 9.3
- **Description:** This vulnerability affects the Azure Stack and could be exploited by attackers to gain control of the system. While rated as "Exploitation Less Likely," the high CVSS score makes this a significant concern for Azure Stack users.

### CVE-2024-38140: Reliable Multicast Transport Driver Vulnerability
- **CVSS Score:** 9.8
- **Description:** This vulnerability in the Reliable Multicast Transport Driver (RMCAST) is critical, with the potential for remote code execution. Exploitation is less likely, but the severity of this issue warrants close attention.

## Recommendations

- **Patch Immediately:** Given the severity and exploitability of some of these vulnerabilities, it is recommended that organizations and individuals apply the August 2024 security patches as soon as possible.
- **Monitor Systems:** Continuous monitoring for signs of exploitation, especially for the vulnerabilities rated as "Exploitation Detected" and "Exploitation More Likely."
- **Review Workarounds and Mitigations:** While many vulnerabilities do not have specific workarounds or mitigations, review Microsoft's recommendations to ensure any possible risk is minimized.

## Conclusion

The August 2024 security updates from Microsoft highlight the importance of regular patching and vigilance in maintaining cybersecurity. With critical vulnerabilities spanning across Windows, Azure, Office, and other Microsoft services, timely application of these updates is essential to protect systems from potential exploitation.

For more details and the full list of addressed CVEs, refer to [the official Microsoft documentation](https://msrc.microsoft.com/update-guide/releaseNote/2024-Aug).
