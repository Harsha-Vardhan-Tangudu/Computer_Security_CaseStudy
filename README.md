# Computer_Security_CaseStudy
# LA County Health Services: Patient’s Data Exposed in Phishing Attack

## Overview

This report details a case study on a phishing attack targeting the LA County Department of Health Services (DHS) in February 2024. This attack resulted in a data breach compromising approximately 23 employees' email accounts, exposing sensitive patient information.

## Contents

1. [Introduction](#introduction)
2. [Details of the Phishing Attack](#details-of-the-phishing-attack)
3. [Steps Taken to Restore Security](#steps-taken-to-restore-security)
4. [Examples of Effective Phishing Techniques](#examples-of-effective-phishing-techniques)
5. [Attacker's Strategy](#attackers-strategy)
6. [Past Breaches and Losses](#past-breaches-and-losses)
7. [Analysis](#analysis)
8. [Reference Paper Solutions](#reference-paper-solutions)
9. [Team Solution](#team-solution)
10. [References](#references)

## Introduction

Phishing attacks are increasingly prevalent, with 94% of organizations worldwide falling victim in 2024. This report analyzes the phishing attack on LA County DHS, highlighting the breach details, the attacker's strategy, and mitigation measures.

## Details of the Phishing Attack

### Incident Overview

- **Location:** LA County, California
- **Date:** February 19-20, 2024
- **Target:** LA County Department of Health Services (DHS)
- **Compromise:** Approximately 23 employees' email accounts

### Exposed Information

- Personal Information: First and last names, date of birth, home address, phone numbers, email address, medical record number, client identification number, dates of service
- Medical Information: Diagnosis/condition, treatment, test results, medications
- Health Plan Information

### Not Exposed

- Social Security Numbers (SSNs)

## Steps Taken to Restore Security

1. Disabled compromised email accounts.
2. Re-set and re-imaged affected employee devices.
3. Quarantined suspicious incoming emails.
4. Warned employees to scrutinize emails, especially attachments or links.
5. Advised patients to review personal and health records for potential data manipulation.

## Examples of Effective Phishing Techniques

1. **Utilizing Public Information:** Crafting phishing emails based on publicly available company information, such as annual celebrations.
2. **Tailoring to Interests:** Sending targeted phishing emails based on the recipient's interests.
3. **TYPO-SQUATTING:** Using domain names or email addresses with slight variations to confuse victims and lead them to malicious links.
4. **Embedding Malicious Code:** Using steganography to hide malicious code within images.

## Attacker's Strategy

### Phase 1: Reconnaissance

- Conducted footprinting on employees using social media and other online resources.
- Employed techniques like Google Dorking and vishing calls to gather emails.

### Phase 2: Scanning

- Identified system details such as operating system, open ports, company architecture, and firewall configurations.

### Phase 3: Gaining Access

- Sent phishing emails containing links or attachments with backdoors, remote access Trojans (RATs), or keyloggers.

### Phase 4: Persistence

- Used obfuscation techniques to maintain access even after initial malicious files were removed.

### Phase 5: Clearing Tracks

- Removed evidence of the attack to avoid detection.

## Past Breaches and Losses

- **2012-2024:** Multiple attacks reported on LA County and its health departments.
- **2017:** Phishing email attack compromising SSNs.
- **2021:** Phishing email attack on LA County Mental Health Services.
- **2023:** MFA phishing attack on the Department of Children's and Family Services (DCFS).
- **2024:** MFA phishing attack on LA County Mental Health Services.

## Analysis

Repeated breaches in public health services undermine patient trust, necessitating urgent improvements in cybersecurity and transparent communication to rebuild trust.

## Reference Paper Solutions

### Paper 1: Phishing Attacks and Protection Against Them

**Key Points:**

- Types of phishing: spear phishing, vishing, smishing
- Techniques: Email attachments with keyloggers or ransomware, malicious file formats, cloud service threats, banking Trojans, CSRF attacks

**Solutions:**

1. Regular software updates, including antivirus.
2. Verify sender addresses and attachments.
3. Use two-factor authentication.
4. Avoid downloading suspicious attachments.
5. Backup important files.
6. Report suspicious emails.

### Paper 2: Prevention of Phishing Attacks: A Three-Pillared Approach

**Key Points:**

- One-time password (OTP)
- Multi-level desktop barrier applications
- Behavior modification

**Solutions:**

1. Implement OTP for additional security.
2. Use desktop barrier applications to prevent access to suspicious websites.
3. Educate employees about typical phishing signs and behavior modification.

## Team Solution

Implement proxy servers to filter and block suspicious URLs, focus on HTTP and TYPO-SQUATTING, and monitor web application traffic. Use updated antivirus software and ensure regular employee training on phishing awareness.

## References

1. [Phishing Statistics 2024](https://www.egress.com/blog/phishing/phishing-statistics-round-up#:~:text=Important%20phishing%20statistics%20for%202024&text=94%25%20of%20organizations%20were%20victims,suffered%20from%20account%20takeover%20attacks.)
2. [Email Risk Report](https://pages.egress.com/whitepaper-email-risk-report-01-24.html)
3. [SSA on SSNs](https://www.ssa.gov/policy/docs/ssb/v69n2/v69n2p55.html#:~:text=Assigned%20at%20birth%2C%20the%20SSN,track%20an%20individual's%20financial%20information.)
4. [Phases of Ethical Hacking](https://www.infosectrain.com/blog/phases-of-ethical-hacking/)
5. [DHS Notice of Data Breach](https://dhs.lacounty.gov/public-and-media-relations/home/notice-of-data-breach/)
6. [APWG Trends Report Q4 2023](https://docs.apwg.org/reports/apwg_trends_report_q4_2023.pdf)
7. [MFA Bypassed Cyberattack](https://www.hipaajournal.com/mfa-bypased-cyberattack-la-county-department-mental-health/#:~:text=Los%20Angeles%20County%20Department%20of%20Mental%20Health&text=The%20cyber%20threat%20actors%20bypassed,that%20they%20will%20eventually%20respond.)
8. [LA County Data Breach on Twitter](https://twitter.com/search?q=la%20county%20data%20breach&src=typed_query)
9. [California Attorney General Data Breach List](https://oag.ca.gov/privacy/databreach/list)
10. [Project Hound Press Release](https://file.lacounty.gov/SDSInter/dmh/1153322_ProjectHoundPressRelease122223FINAL.pdf)
11. [LAist on Cyberattack](https://laist.com/brief/news/health/la-county-department-of-mental-health-announces-it-was-victim-of-cyberattack)
12. [Typo-Squatting](https://medium.com/@mehervardhan/not-ee-pad-hah-typo-squatting-40fb7a70e39a)

---

This README file provides a comprehensive overview of the phishing attack on LA County DHS, detailing the incident, analysis, and solutions. For more information, refer to the provided links and references.
