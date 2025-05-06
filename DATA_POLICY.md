# Brenta — Data Policy (v1.0 – 5 May 2025)

## 1  Purpose & philosophy

Brenta’s work sits at the crossroads of marketing, data and public-interest design. Our goal is to **win attention without abusing attention**. This document sets out the baseline obligations we *must* meet under European law and the additional voluntary safeguards we adopt to protect individual autonomy and the public sphere.

**Who must follow this policy?** Every employee, contractor, client‑side embed and supplier who designs, approves or runs digital campaigns under the Brenta name.

## 2  Scope

* **Activities** – online advertising, search‑engine optimisation, audience analytics, creative testing, and any machine‑learning tooling used in those contexts.
* **Territory** – Users located in the European Economic Area (EEA) or whose data is processed on EEA‑based infrastructure.
* **Data** – All personal data, including behavioural telemetry and any biometric or soft‑biometric signal.

## 3  Guiding principles

1. **Legality first** – Comply with the letter of GDPR, e‑Privacy, DSA, the AI Act and allied sectoral rules.
2. **Minimisation by design** – Collect only what is strictly necessary; aggregate or anonymise wherever feasible.
3. **Autonomy & dignity** – Avoid practices that exploit cognitive biases, vulnerabilities or unconscious states.
4. **Accountability** – Keep auditable records and accept joint‑controller status where platforms require it.
5. **Radical transparency** – Give users a clear, plain‑language explanation of targeting logic and opt‑out routes.

## 4  Regulatory & ethical matrix

| Framework (status)                                              | Binding obligations (minimum)                                                                                                                  | Brenta voluntary commitments                                                                                                                      |
| --------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------- |
| **GDPR & e‑Privacy**<br>(in force)                              | • Lawful basis for every data point.<br>• No special‑category data without explicit consent.<br>• Joint‑controller agreements signed & stored. | • Exclude segments signalling vulnerability (e.g., minors, compulsive night‑time browsing).<br>• Auto‑delete raw logs 60 days after campaign end. |
| **Digital Services Act**<br>(platform duties live)              | • Truthful “paid‑for‑by” field & targeting schema.<br>• No dark‑pattern landing pages.                                                         | • Show key claim in the ad itself to reduce rage‑click loops.<br>• Honour data‑access requests from vetted researchers.                           |
| **AI Act Art 5(1)(a‑b)**<br>(ban from 2 Feb 2025)               | • Refuse any feature that covertly exploits vulnerabilities or subliminally distorts behaviour causing likely significant harm.                | • Avoid pure engagement optimisation even if lawful; privilege outcome or value‑based KPIs.                                                       |
| **Political‑Ads Regulation**<br>(from Oct 2025)                 | • Mandatory disclosure + repository entry.<br>• **No micro‑targeting** with sensitive or inferred political traits.                            | • Provide a concise “Why you see this ad” notice for *all* campaigns, political or commercial.                                                    |
| **Soft‑biometric emotion AI**<br>(future Annex III “high‑risk”) | • Use only if module has EU AI‑database entry & CE‑mark.                                                                                       | • Require internal ethics review before any test or pilot; publish summary findings.                                                              |

## 5  Operational controls

* **Lawful‑basis register** – Template stored in `/datagov/registers/lawful_basis.yaml`. Every campaign entry must be completed before launch.
* **Campaign risk checklist** – 10‑point form covering vulnerable audiences, manipulation red‑flags, disinformation vectors.
* **Data‑retention schedule** – See `/datagov/retention_policy.md`; defaults: 60 days raw logs, 18 months aggregated stats, 36 months anonymised benchmarks.
* **Incident log** – Any user complaint, data leak or disinformation escalation recorded in `/incidents/YYYY-MM-DD_<slug>.md` within 24 h.

## 6  Governance & review

* **Policy owner** – Data Protection Officer (`dpo@brenta.eu`).
* **Next review** – November 2025 (or sooner if EU law changes materially).
* **Approval chain** – Draft by DPO → review by Legal Counsel → ratification by Managing Partner.

## 7  Version history

| Date       | Version | Notes                                                    |
| ---------- | ------- | -------------------------------------------------------- |
| 2025‑05‑05 | 1.0     | Initial public release, migrated from internal playbook. |

---

> **Disclaimer**  This document is provided for transparency and internal governance. It is not legal advice. Independent legal counsel should be sought for specific client implementations.
