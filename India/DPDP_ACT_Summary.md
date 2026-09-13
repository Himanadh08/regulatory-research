# Digital Personal Data Protection Act 2023 — Summary & GRC Analysis

**Prepared by:** Himanadh Sesha Sai. Inampudi. 
**Date:** 10 september 2026  
**Purpose:** Professional portfolio artifact — GRC knowledge documentation  
**Status:** Active study note — updated as implementation progresses  
**Connect:** ![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue?style=flat&logo=linkedin)
  https://www.linkedin.com/in/himanadh-sesha-sai-inampudi-410b88316?utm_source=share_via&utm_content=profile&utm_medium=member_android
| [YOUR GITHUB URL]
https://github.com/Himanadh08

---

## 1. Overview

The Digital Personal Data Protection Act 2023 (DPDP Act) is India's first comprehensive 
data protection legislation, receiving Presidential assent on August 11, 2023. It governs 
the processing of digital personal data within India and establishes rights for individuals 
(Data Principals) and obligations for organisations processing their data (Data Fiduciaries).

The DPDP Act draws significant influence from the EU's General Data Protection Regulation 
(GDPR) while being structured specifically for India's regulatory and economic context. 
It replaces the data protection provisions previously embedded in the Information 
Technology Act 2000 and marks a fundamental shift in how Indian organisations must 
handle personal data.

**Regulator:** Data Protection Board of India  
**Enforcement:** Rules under the Act are pending finalisation as of mid-2026 — 
organisations are actively preparing compliance frameworks in anticipation of enforcement  
**Administered by:** Ministry of Electronics and Information Technology (MeitY)

---

## 2. Key Definitions

| Term | Definition |
|---|---|
| Data Principal | The individual whose personal data is being processed |
| Data Fiduciary | Any entity that determines the purpose and means of processing personal data |
| Significant Data Fiduciary | A Data Fiduciary designated by the government based on volume, sensitivity, or national security risk |
| Personal Data | Any data about an identifiable individual |
| Data Processor | An entity that processes personal data on behalf of a Data Fiduciary |
| Consent Manager | A registered platform through which individuals can give, manage, review, and withdraw consent |
| Data Protection Board | The quasi-judicial regulatory body established under the Act to adjudicate complaints and impose penalties |
| Processing | Any operation performed on personal data — collection, storage, use, sharing, or deletion |

---

## 3. Scope of the Act

**Applies to:**
- Processing of digital personal data within India
- Processing of digital personal data outside India if it involves offering goods 
  or services to individuals located in India

**Does NOT apply to:**
- Personal data processed for personal or domestic purposes
- Personal data made publicly available by the Data Principal themselves or 
  under a legal obligation
- Certain government exemptions for national security, sovereignty, and 
  law enforcement purposes
- Offline/physical personal data not in digital form

---

## 4. Rights of Data Principals

| Right | What it means in practice |
|---|---|
| Right to information | Know what personal data is being processed, for what purpose, and with whom it is shared |
| Right to correction | Request correction of inaccurate, incomplete, or outdated personal data |
| Right to erasure | Request deletion of personal data when it is no longer necessary for the specified purpose |
| Right to grievance redressal | Raise complaints directly with the Data Fiduciary and escalate unresolved matters to the Data Protection Board |
| Right to nominate | Nominate another individual to exercise data rights in case of the Data Principal's death or incapacity |

**Notable difference from GDPR:** The DPDP Act does not include a Right to Data 
Portability or a Right to Object to processing — both of which exist in GDPR. 
This is a significant gap for organisations that operate under both frameworks 
simultaneously and must navigate the differences carefully.

---

## 5. Obligations of Data Fiduciaries

### 5.1 Consent Requirements
- Consent must be free, specific, informed, unconditional, and unambiguous
- Must be obtained through a clear affirmative action by the Data Principal
- A notice must be provided before seeking consent, explaining what data is 
  collected and for what purpose, in clear and plain language
- Consent must be as easy to withdraw as it was to give
- Historical data processing that occurred before the Act came into force must 
  be regularised — Data Fiduciaries cannot simply rely on pre-existing implied consent

### 5.2 Purpose Limitation
- Personal data may only be processed for the specific purpose for which 
  consent was obtained
- Data cannot be retained beyond what is reasonably necessary for that purpose
- Secondary use of data for unrelated purposes requires fresh consent

### 5.3 Data Minimisation
- Only collect personal data that is strictly necessary for the specified purpose
- Excessive or speculative data collection is prohibited

### 5.4 Security Safeguards
- Data Fiduciaries must implement reasonable technical and organisational 
  security measures to prevent personal data breaches
- In the event of a breach, both the Data Protection Board AND the affected 
  Data Principals must be notified — the timeline for notification is to be 
  specified in the Rules (not yet finalised)

### 5.5 Accuracy of Data
- Reasonable steps must be taken to ensure that personal data is accurate 
  and up to date where it is used to make decisions affecting Data Principals 
  or where it is shared with other Data Fiduciaries

### 5.6 Grievance Officer
- Every Data Fiduciary must designate a Grievance Officer whose contact 
  details must be published
- The Grievance Officer must respond to complaints within the timeframe 
  prescribed by the Rules

---

## 6. Significant Data Fiduciaries — Enhanced Obligations

Organisations designated as Significant Data Fiduciaries by the Central Government 
face additional requirements beyond the standard obligations:

- Appoint a **Data Protection Officer** who must be based in India and report 
  to the Board of Directors
- Appoint an independent **Data Auditor** to conduct periodic compliance assessments
- Conduct periodic **Data Protection Impact Assessments (DPIA)** for high-risk 
  processing activities
- Comply with additional requirements as notified by the government from time to time

Designation as a Significant Data Fiduciary is based on factors including the 
volume and sensitivity of personal data processed, the potential risk to Data 
Principals, the impact on national security or public order, and the organisation's 
potential impact on sovereignty or integrity of India.

---

## 7. Children's Data — Special Provisions

- Verifiable parental consent is required before processing personal data of 
  any individual under the age of 18
- Data Fiduciaries must not process children's data in a manner that is 
  detrimental to the wellbeing of the child
- Behavioural tracking of children is explicitly prohibited
- Targeted advertising directed at children is prohibited
- Age verification mechanisms must be implemented before processing — 
  a significant technical and operational challenge for digital platforms

---

## 8. Cross-Border Data Transfers

The DPDP Act permits the transfer of personal data to countries or territories 
notified by the Central Government as permissible transfer destinations. The 
specific whitelist of permitted countries has not been published as of mid-2026, 
making this one of the most operationally uncertain elements of the Act for 
multinational organisations.

**Practical implication:** Until the country whitelist is published, organisations 
with international data flows must proceed cautiously and document their transfer 
rationale. This is an area where GRC professionals are actively advising clients 
on interim measures.

**Contrast with GDPR:** GDPR uses Adequacy Decisions, Standard Contractual Clauses 
(SCCs), and Binding Corporate Rules for cross-border transfers — a significantly more 
detailed and prescriptive mechanism than the DPDP Act's government-notified 
country approach.

---

## 9. Penalty Structure

| Violation | Maximum Penalty |
|---|---|
| Failure to implement security safeguards resulting in a data breach | Rs. 250 crore |
| Failure to notify the Board or Data Principals of a breach | Rs. 200 crore |
| Non-compliance with provisions related to children's data | Rs. 200 crore |
| Non-compliance by a Significant Data Fiduciary | Rs. 150 crore |
| Obstruction of the Data Protection Board | Rs. 150 crore |
| Other violations of the Act | Rs. 50 crore |

Penalties are adjudicated by the Data Protection Board — not courts — making it 
a quasi-judicial authority with significant enforcement power. The Board can 
investigate complaints, conduct inquiries, and impose financial penalties without 
requiring court proceedings for each case.

---

## 10. DPDP Act vs GDPR — Key Comparison

| Aspect | DPDP Act 2023 (India) | GDPR 2018 (European Union) |
|---|---|---|
| Effective date | August 2023 (rules pending) | May 2018 |
| Lawful bases for processing | Primarily consent + certain legitimate uses specified in Schedule | 6 lawful bases including legitimate interest |
| Right to data portability | Not included | Included |
| Right to object to processing | Not included | Included |
| Cross-border data transfers | Government-notified country whitelist | Adequacy Decisions + SCCs + BCRs |
| DPO requirement | Only for Significant Data Fiduciaries | Mandatory for all controllers meeting certain criteria |
| Penalty structure | Up to Rs.250 crore per category of violation | Up to 4% of global annual turnover or €20 million |
| Regulatory body | Data Protection Board (quasi-judicial) | Individual member state supervisory authorities (e.g. ICO in UK, CNIL in France) |
| Extraterritorial scope | Yes — processing related to offering services to individuals in India | Yes — processing related to offering goods or services to EU residents |
| Children's age threshold | Under 18 | Under 16 (minimum 13, varies by member state) |
| Right to erasure | Included | Included (Right to be Forgotten) |
| Data breach notification | To Board + affected Data Principals (timeline in Rules) | Within 72 hours to supervisory authority; without undue delay to individuals |
| Legitimate interests basis | Not available as a lawful basis | Available — widely used by organisations |

---

## 11. Sectors Most Impacted in India

| Sector | Why impacted | Key compliance challenge |
|---|---|---|
| Banking and Financial Services | Large volumes of sensitive financial and identity data | Consent management for existing customer data, cross-border transfers for international transactions |
| Healthcare | Patient records, diagnostic data, genetic information | Data minimisation, retention policies, breach notification |
| E-commerce and Retail | Purchase history, behavioural data, location data | Consent for marketing, children's data if platform allows minor access |
| EdTech | Student data, children's data (major category) | Age verification, parental consent mechanisms, behavioural tracking prohibition |
| Telecom | Location data, call records, communication content | Volume of data, cross-border data flows for international operators |
| Insurance | Health and lifestyle data used for risk assessment | Sensitive data processing, purpose limitation for actuarial use |
| Fintech | Payment data, KYC data, behavioural financial data | RBI compliance intersection, third-party data sharing with lending partners |

---

## 12. GRC Compliance Actions Organisations Must Take

### Immediate actions:
- Conduct a **personal data inventory** — identify all personal data collected, 
  where it is stored, how long it is retained, who has access, and with whom 
  it is shared
- Review and update **privacy notices** to meet DPDP consent notice requirements 
  in clear and plain language
- Implement or upgrade a **consent management mechanism** — particularly critical 
  for digital platforms with large user bases and existing customer relationships
- Designate a **Grievance Officer** and publish their contact details across 
  all customer touchpoints
- Review **data retention schedules** — establish documented timelines and 
  automated deletion processes for data that is no longer required
- Prepare a **data breach response procedure** including identification, 
  containment, assessment, notification drafting, and Board reporting
- Map **third-party data processors** — any vendor or partner processing data 
  on your behalf must have contractual data processing agreements in place

### For Significant Data Fiduciaries:
- Appoint a Data Protection Officer (India-based)
- Engage an independent Data Auditor
- Establish a DPIA process for high-risk processing activities
- Create a dedicated data governance function reporting to senior management

---

## 13. Current Implementation Status (July 2026)

- **August 11, 2023** — DPDP Act received Presidential assent
- **2024** — Draft Rules released for public consultation by MeitY
- **2025–2026** — Rules under finalisation; Data Protection Board not yet constituted
- **Current status** — Most organisations in the pre-enforcement preparation phase, 
  building internal compliance frameworks, mapping data flows, and updating 
  privacy notices in anticipation of enforcement
- **Expected next steps** — Finalisation of Rules, constitution of Data Protection 
  Board, notification of Significant Data Fiduciaries, publication of approved 
  country list for cross-border transfers

---

## 14. Key Resources

- [DPDP Act 2023 — Official Government Text via MeitY](https://www.meity.gov.in/)
- [Ministry of Electronics and Information Technology](https://www.meity.gov.in/)
- [GDPR Official Text for comparison](https://gdpr.eu/what-is-gdpr/)
- [NIST Privacy Framework (useful companion)](https://www.nist.gov/privacy-framework)
- [iSPIRT DPDP Resources](https://ispirt.in/)
- [Data Security Council of India — DPDP resources](https://www.dsci.in/)

---

## 15. Personal Analysis

<!-- 
WRITE THIS YOURSELF — 3 to 4 sentences minimum in your own words.

Answer ONE of these prompts:

Option A: Which obligation do you think most Indian companies are least 
prepared for and why?

Option B: What is the biggest difference between DPDP and GDPR that a GRC 
analyst needs to understand when advising a company with both Indian and EU users?

Option C: Which sector do you think faces the highest compliance risk under 
DPDP and why?

This is the ONLY section you write yourself. Make it genuine — even 
3 honest sentences of your own thinking is worth more than copied text.
-->

*[Write your own analysis here — see prompts above]*

---

## 16. Study Notes

<!-- 
WRITE THIS YOURSELF — optional but adds real value.

Note 1 or 2 things that surprised you while reading about this Act, 
or something you noticed that most people probably miss. 
Even one sentence is fine.
-->

*[Optional — add your own observations here]*

---

*Last updated: July 2026*  
*Author: [YOUR NAME] — Cybersecurity GRC Student, Uttaranchal University*  
*Specialisation: GRC · AI Risk Compliance · Penetration Testing Fundamentals*
