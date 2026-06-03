# PRIVACY NOTICE
### RelojSolarLunar — Desktop Application

> **Drafting notes (remove before publication).** Canonical English version. Updated to reflect (i) the **new Mexican Federal Law on Protection of Personal Data Held by Private Parties (LFPDPPP)** published in the DOF on **20 March 2025**, in force since 21 March 2025, which repealed the 2010 LFPDPPP; and (ii) the dissolution of **INAI** and the transfer of its competences over private-sector data protection to the **Secretaría Anticorrupción y Buen Gobierno (SABG)**, acting through its **Dirección General de Datos Personales en el Sector Privado**. Bracketed `[ ]` items to confirm before publication.

---

**Effective date of this version:** [DATE]
**Version:** v1.0

---

## 1. Identity of the Data Controller

RelojSolarLunar is developed and distributed by **Carlos Benito Carpintero**, an individual engaged in business activity (*persona física con actividad empresarial*), resident in Mexico City, Mexico (the "Controller", "we", "us", or "our").

- Email (privacy and data-subject requests): **legal@3doce56.com**
- Address for ARCO and notice purposes: **[street address], Alcaldía Benito Juárez, Mexico City, C.P. 03020, Mexico**
- Website: **https://3doce56.com**

The trade name **3doce56** is used for commercial identification; the legal responsible party is the individual identified above.

## 2. Data We Collect

When you purchase and activate RelojSolarLunar, we collect and process the following personal data:

| Category | Data | Source |
|---|---|---|
| Account | Email address | Provided by purchase platform (Gumroad or Microsoft Store) |
| Activation | Activation key; Installation Identifier (a non-reversible SHA-256 hash derived from MAC address, system disk serial, and hostname, recalculated at each launch without local persistence) | Generated at first launch on your device |
| Device | Operating system; application version | Collected automatically at activation |
| Location | Country (derived from IP address at activation) | Collected automatically |
| Usage | Heartbeat timestamps (periodic connectivity signals sent while the application is running) | Collected automatically during use |
| Transaction | Transaction or order identifier | Provided by purchase platform |

**We do not collect:** your full name (other than what may be contained in your email address), payment card details, phone number, or precise geographic location.

**Note on purchase platforms.** Gumroad and Microsoft Store independently process your payment and purchase data under their own privacy policies. We only receive the minimum data necessary to validate your license: your email address and a transaction identifier.

**Necessity of the data.** The data listed above are **necessary for the conclusion and performance of the license contract**. If you do not provide them — for example, by refusing to activate the Software or by blocking the license-validation traffic — the Software cannot be activated or, if already activated, will operate in degraded mode (no remote validation, no remote updates of astronomical data) until validation can resume. The Controller does not collect any data beyond what is listed in this Section.

## 3. Purposes of Processing

### Purposes necessary for the performance of the contract

1. **License validation** — to verify that your copy is legitimately licensed and to prevent unauthorized use.
2. **Service delivery** — to provide real-time astronomical data (sunrise, sunset, solar noon, moon phase) for your active city.
3. **Session continuity** — heartbeat signals detect active installations and manage permitted use per installation.
4. **Security and anti-piracy** — to detect anomalous activation patterns indicating license sharing or fraud.
5. **Compliance with legal obligations** — to maintain records of privacy notice acceptance as required by law.

### Secondary purpose

6. **Aggregate analytics.** We derive non-identifiable, anonymized, aggregated statistics from your data (e.g., country distribution, operating-system share) **after** removing any identifying elements. Once anonymized, the resulting aggregates are no longer personal data and are not subject to your individual rights.

If you wish to **object to the processing of your personal data prior to anonymization** (and therefore to your data being included in the inputs to the aggregate analytics process), email **legal@3doce56.com**.

## 4. Legal Bases for Processing

| Purpose | Legal basis (Mexico — LFPDPPP) | Legal basis (EU — GDPR) |
|---|---|---|
| License validation | Performance of contract | Art. 6(1)(b) — Performance of contract |
| Service delivery | Performance of contract | Art. 6(1)(b) — Performance of contract |
| Session continuity | Performance of contract | Art. 6(1)(b) — Performance of contract |
| Security / anti-piracy | Legitimate interest | Art. 6(1)(f) — Legitimate interest |
| Compliance with legal obligations | Legal obligation | Art. 6(1)(c) — Legal obligation |
| Aggregate analytics | Legitimate interest (data anonymized prior to use) | Art. 6(1)(f) — Legitimate interest |
| Automated detection of license cloning (see Section 11) | Performance of contract | Art. 22(2)(a) — Necessary for the performance of a contract |

References to "LFPDPPP" mean the **Ley Federal de Protección de Datos Personales en Posesión de los Particulares** published in the DOF on 20 March 2025 and in force since 21 March 2025.

## 5. Retention Periods

| Data | Retention |
|---|---|
| Raw activation and heartbeat records | 90-day rolling window; older records deleted automatically |
| Aggregated, non-identifiable, anonymized statistics | Retained indefinitely (no longer personal data) |
| Privacy notice acceptance record | Life of the license plus the minimum period required by applicable law |
| Operational backups (developer-side) | Maximum **24 months** rolling, then overwritten |

## 6. Recipients of Your Data

- **Resend** (Resend Inc., United States) — transactional email; used solely to send activation confirmation messages. Privacy policy: `resend.com/legal/privacy-policy`
- **Cloud infrastructure provider** — our backend database is hosted on a cloud virtual machine. As of the effective date, the provider is **[Oracle Cloud Infrastructure — México Central region (Querétaro)]**.

**Gumroad and Microsoft Store are not recipients under this notice.** They are independent data controllers with respect to purchase and payment data.

## 7. International Data Transfers

The Controller is established in Mexico. This means that **when a User located in the European Union, the European Economic Area, or another jurisdiction outside Mexico purchases or activates the Software**, their personal data are transferred to Mexico for processing.

### 7.1 Transfer from the EU/EEA to Mexico

The European Commission has not issued an adequacy decision for Mexico under Article 45 GDPR. The transfer of your personal data from the EU/EEA to the Controller in Mexico is conducted on the following legal basis:

**Article 49(1)(b) GDPR — Transfer necessary for the performance of a contract.** The transfer is necessary for the performance of the license contract between you and the Controller, concluded by your purchase and activation of the Software. Without the transfer of the minimum data described in Section 2 to the Controller's backend in Mexico, the license cannot be validated and the Software cannot be operated.

By accepting this Notice and activating the Software, you are informed of and acknowledge this transfer.

### 7.2 Onward transfer to the United States (transactional email)

Your email address is transferred to **Resend** (Resend Inc., United States) solely to send activation confirmation messages. This onward transfer is protected by Resend's participation in the **EU–U.S. Data Privacy Framework (DPF)** and/or **Standard Contractual Clauses (SCCs)** approved by the European Commission.

### 7.3 Where data are stored

The Controller's backend infrastructure is hosted on **[Oracle Cloud Infrastructure — México Central region (Querétaro)]**. Operational and license-validation data therefore reside in Mexico, with the exception of the email-address transfer to Resend described above.

## 8. Your Rights

You have the following rights, known in Mexico as **ARCO rights** (*Acceso, Rectificación, Cancelación, Oposición*), supplemented by additional rights under the GDPR where applicable:

| Right | Description |
|---|---|
| Access | Obtain confirmation that we process your data and receive a copy |
| Rectification | Request correction of inaccurate or incomplete data |
| Cancellation / Erasure | Request deletion of your data, subject to legal retention obligations |
| Opposition | Object to processing based on legitimate interest or for purposes you do not wish |
| Withdrawal of consent | Where processing is based on consent, revoke that consent at any time without retroactive effect |
| Data portability (GDPR) | Receive your data in a structured, commonly used, machine-readable format |
| Restriction (GDPR) | Request restriction of processing in certain circumstances |

**How to exercise your rights.** Send a request to **legal@3doce56.com** including: (i) your name and a means to contact you; (ii) documents that reasonably evidence your identity (or, in the case of a representative, their identity and authority); (iii) a clear and precise description of the data concerned and of the right you are exercising; (iv) any other element that helps locate your data (for example, your activation Installation Identifier or the email used to purchase). Requests concerning your personal data are accepted and handled in **any language**; the general limitation to English and Spanish for support and commercial correspondence does not apply to the exercise of these rights.

**Response time.** We will respond within **twenty (20) business days** from receipt of a complete request, as required by the LFPDPPP. If the request is granted, we will give effect to it within **fifteen (15) additional business days**. If the request is incomplete, we will notify you within five (5) business days so you may complete it within ten (10) business days. Where justified, the response period may be extended once by the LFPDPPP's permitted term, with prior notice to you.

**Erasure and anonymization.** Where applicable law requires us to retain certain records, we will **anonymize** the data rather than delete it — replacing personal identifiers with irreversible cryptographic hashes — so that the technical record persists without continuing to constitute personal data.

**Recourse.** If you consider that our response is inadequate or that we have processed your data unlawfully, you may file a complaint with the supervisory authority indicated in Section 13.

## 9. Local Storage on Your Device

RelojSolarLunar stores data locally on your device in a SQLite database and a configuration file, containing: astronomical data for your active city (8-day sliding window), your selected city and display preferences, and your installation state.

This data remains on your device and is under your control. You may delete it at any time by uninstalling the application. Local storage does not include tracking cookies or advertising identifiers.

## 10. Security Measures

The Controller has adopted **administrative, technical, and physical security measures** reasonable for the nature and volume of the data processed, including: transport encryption (TLS) for all communications between the application and the backend; restricted access to backend systems based on authentication and the principle of least privilege; operational logging that does not include unnecessary personal data; and periodic review of the security posture.

No security measure can guarantee absolute protection against all risks. The Controller will respond to any data security incident in accordance with applicable law and will notify affected individuals where required.

## 11. Automated Decision-Making

The license validation system operates **automated detection of cloning or fraudulent reuse of a license key** across multiple devices. Where such fraudulent use is detected, the system may revoke the affected Installation Identifiers and, on a second detection affecting the same User, **automatically terminate the license** pursuant to Section 8.1 of the End User License Agreement.

**Logic of the decision.** Detection is based on objective signals from the License Validation Service: in particular, simultaneous use of a single license key by Installation Identifiers that the system identifies as distinct devices, in a pattern incompatible with the two-slot entitlement granted by the license.

**Significance and consequences.** A first detection results in revocation of the affected Installation Identifiers and issuance of a new license key as a one-time remediation; the underlying entitlement is preserved. A subsequent detection results in definitive termination of the license.

**Legal basis.** The automated decision is necessary for the performance of the license contract between the User and the Controller (Article 22(2)(a) GDPR).

**Your safeguards.** You have the right to (i) **obtain human intervention** from the Controller in respect of the decision; (ii) **express your point of view** regarding the detection; and (iii) **contest the decision**. To exercise these rights, contact **legal@3doce56.com** within thirty (30) days from the date you were notified of the decision. The Controller will review the case substantively and respond within twenty (20) business days from receipt of your request.

## 12. Minors

RelojSolarLunar is intended for use by **adults (18 years of age or older)**. The nature and volume of the personal data described in Section 2 are minimal and not designed to identify minors. The Controller does **not** verify the age of users at the time of purchase or activation and does **not** knowingly collect personal data of minors.

If a parent or legal guardian believes that a minor has activated the application, please contact **legal@3doce56.com**. Upon verification, we will delete the associated data and, where possible, the corresponding installation will be deactivated.

## 13. Changes to This Notice

The Controller may update this Privacy Notice from time to time. The version number and effective date will be updated with each change.

- **Material changes** (changes affecting the categories of data collected, the purposes of processing, the recipients, or your rights) will be notified to existing users **in-application on next launch and/or by email**, and will take effect at the indicated effective date.
- **Non-material changes** (clarifications, corrections, references to legal authorities, contact details) will be published on the website without individual notification.

New users always accept the current version at activation. A version changelog is maintained internally and is available on request.

## 14. Supervisory Authority

- **Mexico (LFPDPPP):** **Secretaría Anticorrupción y Buen Gobierno**, **Dirección General de Datos Personales en el Sector Privado** — successor to INAI in matters of personal data held by private parties, pursuant to the constitutional reform of 20 December 2024 and the new LFPDPPP of 20 March 2025. Federal government portal: **gob.mx**.
- **European Union / EEA:** the data protection authority of your country of residence.

## 15. Applicable Law and Jurisdiction

This Notice is governed by the laws of Mexico, specifically the LFPDPPP (DOF 20/03/2025) and, where applicable, the EU GDPR. Disputes not subject to mandatory consumer-protection or data-protection authority jurisdiction shall be resolved by the competent courts of Mexico City.

## 16. Effective Date

This Privacy Notice is effective as of **[DATE]**, version **1.0**.

---

## Contact

**Carlos Benito Carpintero** (commercial name **3doce56**)
Legal: **legal@3doce56.com** · **3doce56.com**
