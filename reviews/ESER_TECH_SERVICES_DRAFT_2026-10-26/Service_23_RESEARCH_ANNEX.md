# ESER TECH — Finance Operations, Invoicing & Payment Automation

GitBook page ID: `oq1qB6cnXttOt64aZrjh` · existing word count 7565 · staged candidate count 9174 · target **20,000+** (NOT YET MET)

This document contains the **new appendix** staged in GitBook draft change request #3, not the original existing chapter text.

### Research Goldmine expansion — service 23 (draft, 26 October 2026)

**Research classification:** This additional service-specific evaluation is not a delivered client project, not a production test, and not founder acceptance. It preserves the professional-service-versus-future-SaaS distinction. Only documented evidence may be used as an observation; video creator claims remain unverified until ESER reproduces them.

#### Evidence-backed opportunity designs

**Scenario 1: milestone invoices for approved client deliverables.** Start with a written discovery interview identifying beneficiary roles, authority to access assets, failure cost, budget and acceptance approver. Narrow the pilot to one measurable result, provide a working demonstration or sample deliverable, and record what the client actually accepted. Avoid converting a hypothetical scenario into a false claim of ESER past work.

**Scenario 2: subscription payment reconciliation with refund ledger.** Start with a written discovery interview identifying beneficiary roles, authority to access assets, failure cost, budget and acceptance approver. Narrow the pilot to one measurable result, provide a working demonstration or sample deliverable, and record what the client actually accepted. Avoid converting a hypothetical scenario into a false claim of ESER past work.

**Scenario 3: vendor bill intake requiring dual approval.** Start with a written discovery interview identifying beneficiary roles, authority to access assets, failure cost, budget and acceptance approver. Narrow the pilot to one measurable result, provide a working demonstration or sample deliverable, and record what the client actually accepted. Avoid converting a hypothetical scenario into a false claim of ESER past work.

**Scenario 4: cash collection reminders restricted by contract.** Start with a written discovery interview identifying beneficiary roles, authority to access assets, failure cost, budget and acceptance approver. Narrow the pilot to one measurable result, provide a working demonstration or sample deliverable, and record what the client actually accepted. Avoid converting a hypothetical scenario into a false claim of ESER past work.

#### Deliverable packages and boundaries

- **Package 1:** invoice numbering, tax configuration and approval policy. Record source inputs, creator or vendor rights, review owner, dependency on external accounts, a priced or separately billable scope assumption, the acceptance artifact and the client handoff owner. Do not include ongoing subscriptions silently within a fixed project fee.
- **Package 2:** payment provider integration and settlement reconciliation. Record source inputs, creator or vendor rights, review owner, dependency on external accounts, a priced or separately billable scope assumption, the acceptance artifact and the client handoff owner. Do not include ongoing subscriptions silently within a fixed project fee.
- **Package 3:** refund, dispute and chargeback evidence handling. Record source inputs, creator or vendor rights, review owner, dependency on external accounts, a priced or separately billable scope assumption, the acceptance artifact and the client handoff owner. Do not include ongoing subscriptions silently within a fixed project fee.
- **Package 4:** audit trail, access control and handoff to licensed accountant. Record source inputs, creator or vendor rights, review owner, dependency on external accounts, a priced or separately billable scope assumption, the acceptance artifact and the client handoff owner. Do not include ongoing subscriptions silently within a fixed project fee.

#### Open-source and free-tier research options

- **ToolJet:** [reference/source](https://github.com/ToolJet/ToolJet). AGPL-3.0 administrative dashboard candidate. This is an evaluated candidate rather than approved deployment. Before claiming “free,” confirm exact code license, hosted billing, model inference fees, trademark/media rights, scaling limits, maintenance responsibility and data processing terms.
- **n8n:** [reference/source](https://github.com/n8n-io/n8n). fair-code event routing with approval boundary. This is an evaluated candidate rather than approved deployment. Before claiming “free,” confirm exact code license, hosted billing, model inference fees, trademark/media rights, scaling limits, maintenance responsibility and data processing terms.
- **Supabase:** [reference/source](https://github.com/supabase/supabase). open core; enforce immutable financial event log. This is an evaluated candidate rather than approved deployment. Before claiming “free,” confirm exact code license, hosted billing, model inference fees, trademark/media rights, scaling limits, maintenance responsibility and data processing terms.
- **Twenty CRM:** [reference/source](https://github.com/twentyhq/twenty). AGPL-3.0 quote and customer record candidate. This is an evaluated candidate rather than approved deployment. Before claiming “free,” confirm exact code license, hosted billing, model inference fees, trademark/media rights, scaling limits, maintenance responsibility and data processing terms.

#### Reproducible acceptance and QA test cases

- **Test 1 — duplicate webhook does not generate duplicate invoice.** Specify setup and test input, expected observable output, pass/fail threshold, evidence screenshot or log, designated test operator, and remediation procedure. Run both successful and negative-path tests in a nonproduction environment where possible. A video or vendor landing page alone does not prove this ESER capability works.
- **Test 2 — partial refund reconciles correctly against original sale.** Specify setup and test input, expected observable output, pass/fail threshold, evidence screenshot or log, designated test operator, and remediation procedure. Run both successful and negative-path tests in a nonproduction environment where possible. A video or vendor landing page alone does not prove this ESER capability works.
- **Test 3 — unapproved vendor payment cannot be initiated.** Specify setup and test input, expected observable output, pass/fail threshold, evidence screenshot or log, designated test operator, and remediation procedure. Run both successful and negative-path tests in a nonproduction environment where possible. A video or vendor landing page alone does not prove this ESER capability works.
- **Test 4 — tax and invoice fields match local expert advice.** Specify setup and test input, expected observable output, pass/fail threshold, evidence screenshot or log, designated test operator, and remediation procedure. Run both successful and negative-path tests in a nonproduction environment where possible. A video or vendor landing page alone does not prove this ESER capability works.
- **Test 5 — failed settlement prompts exception report.** Specify setup and test input, expected observable output, pass/fail threshold, evidence screenshot or log, designated test operator, and remediation procedure. Run both successful and negative-path tests in a nonproduction environment where possible. A video or vendor landing page alone does not prove this ESER capability works.

#### Cost, commercial, rights and security risk register

- **Risk 1: unauthorized movement of funds.** Record the owner of this risk, likelihood and impact, contractual control, evidence of tool/license compatibility, incident escalation route, and minimum mitigation required before accepting client funds. Do not use blanket 'free forever' or 'guaranteed' language.
- **Risk 2: incorrect local tax/legal advice.** Record the owner of this risk, likelihood and impact, contractual control, evidence of tool/license compatibility, incident escalation route, and minimum mitigation required before accepting client funds. Do not use blanket 'free forever' or 'guaranteed' language.
- **Risk 3: payment card handling outside compliant processor.** Record the owner of this risk, likelihood and impact, contractual control, evidence of tool/license compatibility, incident escalation route, and minimum mitigation required before accepting client funds. Do not use blanket 'free forever' or 'guaranteed' language.

#### Practical client-outcome measurements

- **Metric 1: unreconciled payment count.** Capture a baseline, the source system, reporting frequency, data ownership, exclusion conditions and a realistic target only after the client supplies history. Distinguish an ESER-delivered artifact from a business outcome driven by factors ESER does not control.
- **Metric 2: time to collect accepted invoices.** Capture a baseline, the source system, reporting frequency, data ownership, exclusion conditions and a realistic target only after the client supplies history. Distinguish an ESER-delivered artifact from a business outcome driven by factors ESER does not control.
- **Metric 3: billing dispute rate.** Capture a baseline, the source system, reporting frequency, data ownership, exclusion conditions and a realistic target only after the client supplies history. Distinguish an ESER-delivered artifact from a business outcome driven by factors ESER does not control.

#### Video reference queue (source research, not independently reproduced code)

- **Candidate 1:** [Claude AI Scaffolds 3D Interactive Web Dashboard with Stripe & Square UI](https://www.facebook.com/reel/1585001042880687) — registry tier `TIER_5_LIVE_CHROME_WALKTHROUGH`; uploader/creator label: Nocode Joshua (Joshua Stevenson). Evaluate original frames/transcript, validate any code, terms and commercial claims, then accept or reject applicability for this service.
- **Candidate 2:** [488K views · 7.7K reactions | System Design: Building a Bulletproof Payment Gateway! 🚀 Basic payment set](https://www.facebook.com/share/v/1Ga27G9d6c/) — registry tier `TIER_2_TECHNICAL_EXTRACT`; uploader/creator label: KodeKloud. Evaluate original frames/transcript, validate any code, terms and commercial claims, then accept or reject applicability for this service.
- **Candidate 3:** [4.1K views · 541 reactions | 🚀 This AI tool could completely change the way you build production-ready a](https://www.facebook.com/share/r/1C7QKhni5T/) — registry tier `TIER_2_TECHNICAL_EXTRACT`; uploader/creator label: Saurabh Srivastava. Evaluate original frames/transcript, validate any code, terms and commercial claims, then accept or reject applicability for this service.
- **Candidate 4:** [23K views · 77 reactions | Someone just released an AI whose entire job is to build a business 🤯💰 You l](https://www.facebook.com/share/r/1EZUyoegho/) — registry tier `TIER_2_TECHNICAL_EXTRACT`; uploader/creator label: Sebastian Dziura. Evaluate original frames/transcript, validate any code, terms and commercial claims, then accept or reject applicability for this service.
- **Candidate 5:** [7K reactions · 1K shares | Most people think a balance sheet shows the truth. It doesn't. It shows a vers](https://www.facebook.com/share/r/1Efckckne9/) — registry tier `TIER_3_MEDIA_TRANSCRIPT_QA`; uploader/creator label: Onedollar.vault. Evaluate original frames/transcript, validate any code, terms and commercial claims, then accept or reject applicability for this service.
- **Candidate 6:** [3.5K reactions · 523 shares | Comment “COOL” and I’ll send you the complete guide + free template. 🚀 Eve](https://www.facebook.com/share/r/19Ny7xaHNR/) — registry tier `TIER_3_MEDIA_TRANSCRIPT_QA`; uploader/creator label: Greta. Evaluate original frames/transcript, validate any code, terms and commercial claims, then accept or reject applicability for this service.
- **Candidate 7:** [751 reactions · 86 shares | Comment “COOL” and I’ll send you the complete guide + free template. 🚀 Every](https://www.facebook.com/share/r/1C179EDMrf/) — registry tier `TIER_3_MEDIA_TRANSCRIPT_QA`; uploader/creator label: Greta. Evaluate original frames/transcript, validate any code, terms and commercial claims, then accept or reject applicability for this service.

**Relevant source baseline:** [original ESER TECH live documentation](https://eser-tech.gitbook.io/eser-tech-locked-business-plan/); [cross-PC evidence reconciliation](https://github.com/dopefoxes/dopefoxes/blob/main/reviews/ESER_TECH_VIDEO_EVIDENCE_RECONCILIATION_2026-10-26.md). The 290 Aman additional clips are outside V6; 118 status flags conflict with dossier labels. Video metadata does not imply technique reproduction or approved commercial usage.

