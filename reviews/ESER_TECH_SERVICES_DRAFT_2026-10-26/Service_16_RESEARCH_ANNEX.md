# ESER TECH — Appointment Scheduling, Booking & Client Onboarding Systems

GitBook page ID: `qklx0rnUZuTWZIJt57WC` · existing word count 7622 · staged candidate count 9216 · target **20,000+** (NOT YET MET)

This document contains the **new appendix** staged in GitBook draft change request #3, not the original existing chapter text.

### Research Goldmine expansion — service 16 (draft, 26 October 2026)

**Research classification:** This additional service-specific evaluation is not a delivered client project, not a production test, and not founder acceptance. It preserves the professional-service-versus-future-SaaS distinction. Only documented evidence may be used as an observation; video creator claims remain unverified until ESER reproduces them.

#### Evidence-backed opportunity designs

**Scenario 1: salon appointment scheduling with staff capacity.** Start with a written discovery interview identifying beneficiary roles, authority to access assets, failure cost, budget and acceptance approver. Narrow the pilot to one measurable result, provide a working demonstration or sample deliverable, and record what the client actually accepted. Avoid converting a hypothetical scenario into a false claim of ESER past work.

**Scenario 2: clinic intake form without providing clinical advice.** Start with a written discovery interview identifying beneficiary roles, authority to access assets, failure cost, budget and acceptance approver. Narrow the pilot to one measurable result, provide a working demonstration or sample deliverable, and record what the client actually accepted. Avoid converting a hypothetical scenario into a false claim of ESER past work.

**Scenario 3: consultancy discovery meetings with qualification.** Start with a written discovery interview identifying beneficiary roles, authority to access assets, failure cost, budget and acceptance approver. Narrow the pilot to one measurable result, provide a working demonstration or sample deliverable, and record what the client actually accepted. Avoid converting a hypothetical scenario into a false claim of ESER past work.

**Scenario 4: tour booking with deposits and cancellations.** Start with a written discovery interview identifying beneficiary roles, authority to access assets, failure cost, budget and acceptance approver. Narrow the pilot to one measurable result, provide a working demonstration or sample deliverable, and record what the client actually accepted. Avoid converting a hypothetical scenario into a false claim of ESER past work.

#### Deliverable packages and boundaries

- **Package 1:** slot state machine and concurrency policy. Record source inputs, creator or vendor rights, review owner, dependency on external accounts, a priced or separately billable scope assumption, the acceptance artifact and the client handoff owner. Do not include ongoing subscriptions silently within a fixed project fee.
- **Package 2:** calendar/account integration permission and timezone map. Record source inputs, creator or vendor rights, review owner, dependency on external accounts, a priced or separately billable scope assumption, the acceptance artifact and the client handoff owner. Do not include ongoing subscriptions silently within a fixed project fee.
- **Package 3:** cancellation, waitlist and notification policy. Record source inputs, creator or vendor rights, review owner, dependency on external accounts, a priced or separately billable scope assumption, the acceptance artifact and the client handoff owner. Do not include ongoing subscriptions silently within a fixed project fee.
- **Package 4:** intake consent and staff service instructions. Record source inputs, creator or vendor rights, review owner, dependency on external accounts, a priced or separately billable scope assumption, the acceptance artifact and the client handoff owner. Do not include ongoing subscriptions silently within a fixed project fee.

#### Open-source and free-tier research options

- **n8n:** [reference/source](https://github.com/n8n-io/n8n). fair-code workflow hooks; account controls required. This is an evaluated candidate rather than approved deployment. Before claiming “free,” confirm exact code license, hosted billing, model inference fees, trademark/media rights, scaling limits, maintenance responsibility and data processing terms.
- **Supabase:** [reference/source](https://github.com/supabase/supabase). Postgres core for capacity and booking integrity. This is an evaluated candidate rather than approved deployment. Before claiming “free,” confirm exact code license, hosted billing, model inference fees, trademark/media rights, scaling limits, maintenance responsibility and data processing terms.
- **Next.js:** [reference/source](https://github.com/vercel/next.js). MIT application UI. This is an evaluated candidate rather than approved deployment. Before claiming “free,” confirm exact code license, hosted billing, model inference fees, trademark/media rights, scaling limits, maintenance responsibility and data processing terms.
- **ToolJet:** [reference/source](https://github.com/ToolJet/ToolJet). AGPL-3.0 operational dashboard candidate. This is an evaluated candidate rather than approved deployment. Before claiming “free,” confirm exact code license, hosted billing, model inference fees, trademark/media rights, scaling limits, maintenance responsibility and data processing terms.

#### Reproducible acceptance and QA test cases

- **Test 1 — simultaneous booking attempts cannot oversell a slot.** Specify setup and test input, expected observable output, pass/fail threshold, evidence screenshot or log, designated test operator, and remediation procedure. Run both successful and negative-path tests in a nonproduction environment where possible. A video or vendor landing page alone does not prove this ESER capability works.
- **Test 2 — time-zone and daylight saving conversions checked.** Specify setup and test input, expected observable output, pass/fail threshold, evidence screenshot or log, designated test operator, and remediation procedure. Run both successful and negative-path tests in a nonproduction environment where possible. A video or vendor landing page alone does not prove this ESER capability works.
- **Test 3 — cancellation creates correct capacity release and refund request.** Specify setup and test input, expected observable output, pass/fail threshold, evidence screenshot or log, designated test operator, and remediation procedure. Run both successful and negative-path tests in a nonproduction environment where possible. A video or vendor landing page alone does not prove this ESER capability works.
- **Test 4 — reminder messages opt-out respected.** Specify setup and test input, expected observable output, pass/fail threshold, evidence screenshot or log, designated test operator, and remediation procedure. Run both successful and negative-path tests in a nonproduction environment where possible. A video or vendor landing page alone does not prove this ESER capability works.
- **Test 5 — failed calendar API call safely retries without double booking.** Specify setup and test input, expected observable output, pass/fail threshold, evidence screenshot or log, designated test operator, and remediation procedure. Run both successful and negative-path tests in a nonproduction environment where possible. A video or vendor landing page alone does not prove this ESER capability works.

#### Cost, commercial, rights and security risk register

- **Risk 1: double bookings and lost deposits.** Record the owner of this risk, likelihood and impact, contractual control, evidence of tool/license compatibility, incident escalation route, and minimum mitigation required before accepting client funds. Do not use blanket 'free forever' or 'guaranteed' language.
- **Risk 2: storing unnecessary sensitive client data.** Record the owner of this risk, likelihood and impact, contractual control, evidence of tool/license compatibility, incident escalation route, and minimum mitigation required before accepting client funds. Do not use blanket 'free forever' or 'guaranteed' language.
- **Risk 3: payment and cancellation disputes.** Record the owner of this risk, likelihood and impact, contractual control, evidence of tool/license compatibility, incident escalation route, and minimum mitigation required before accepting client funds. Do not use blanket 'free forever' or 'guaranteed' language.

#### Practical client-outcome measurements

- **Metric 1: booking confirmation accuracy.** Capture a baseline, the source system, reporting frequency, data ownership, exclusion conditions and a realistic target only after the client supplies history. Distinguish an ESER-delivered artifact from a business outcome driven by factors ESER does not control.
- **Metric 2: missed appointments.** Capture a baseline, the source system, reporting frequency, data ownership, exclusion conditions and a realistic target only after the client supplies history. Distinguish an ESER-delivered artifact from a business outcome driven by factors ESER does not control.
- **Metric 3: time to complete onboarding.** Capture a baseline, the source system, reporting frequency, data ownership, exclusion conditions and a realistic target only after the client supplies history. Distinguish an ESER-delivered artifact from a business outcome driven by factors ESER does not control.

#### Video reference queue (source research, not independently reproduced code)

- **Candidate 1:** [WA-AKG — self-hosted multi-session WhatsApp gateway/dashboard with API, scheduling, auto-replies and n8n ](https://www.facebook.com/share/r/1EmpMSwAh3/) — registry tier `TIER_6_LOCAL_MP4_AND_DOSSIER_AUDIT`; uploader/creator label: Ikram Rana - AI Automation. Evaluate original frames/transcript, validate any code, terms and commercial claims, then accept or reject applicability for this service.
- **Candidate 2:** [AutoSocial Studio — local multi-account TikTok/Instagram/YouTube scheduling and Playwright upload automat](https://www.facebook.com/share/r/1E5B8ZSim8/) — registry tier `TIER_6_LOCAL_MP4_AND_DOSSIER_AUDIT`; uploader/creator label: Ikram Rana - AI Automation. Evaluate original frames/transcript, validate any code, terms and commercial claims, then accept or reject applicability for this service.
- **Candidate 3:** [33K views · 4.1K reactions | 👇 Comment “GUIDE” for the AI agent cold-call setup Build cold outbound camp](https://www.facebook.com/share/v/1Lp3YWnxR8/) — registry tier `TIER_2_TECHNICAL_EXTRACT`; uploader/creator label: Lead Gen Man. Evaluate original frames/transcript, validate any code, terms and commercial claims, then accept or reject applicability for this service.
- **Candidate 4:** [3.7K reactions · 509 shares | Comment “startup” and I’ll send you the complete guide + all the templates ](https://www.facebook.com/share/r/18E4m5tWy2/) — registry tier `TIER_3_MEDIA_TRANSCRIPT_QA`; uploader/creator label: Greta. Evaluate original frames/transcript, validate any code, terms and commercial claims, then accept or reject applicability for this service.
- **Candidate 5:** [639 reactions · 118 shares | AI automation agency helps businesses capture more leads, answer calls, book](https://www.facebook.com/share/r/198bSDV7X6/) — registry tier `TIER_3_MEDIA_TRANSCRIPT_QA`; uploader/creator label: CashFlow Automations. Evaluate original frames/transcript, validate any code, terms and commercial claims, then accept or reject applicability for this service.
- **Candidate 6:** [3.5K reactions · 523 shares | Comment “COOL” and I’ll send you the complete guide + free template. 🚀 Eve](https://www.facebook.com/share/r/19Ny7xaHNR/) — registry tier `TIER_3_MEDIA_TRANSCRIPT_QA`; uploader/creator label: Greta. Evaluate original frames/transcript, validate any code, terms and commercial claims, then accept or reject applicability for this service.
- **Candidate 7:** [751 reactions · 86 shares | Comment “COOL” and I’ll send you the complete guide + free template. 🚀 Every](https://www.facebook.com/share/r/1C179EDMrf/) — registry tier `TIER_3_MEDIA_TRANSCRIPT_QA`; uploader/creator label: Greta. Evaluate original frames/transcript, validate any code, terms and commercial claims, then accept or reject applicability for this service.

**Relevant source baseline:** [original ESER TECH live documentation](https://eser-tech.gitbook.io/eser-tech-locked-business-plan/); [cross-PC evidence reconciliation](https://github.com/dopefoxes/dopefoxes/blob/main/reviews/ESER_TECH_VIDEO_EVIDENCE_RECONCILIATION_2026-10-26.md). The 290 Aman additional clips are outside V6; 118 status flags conflict with dossier labels. Video metadata does not imply technique reproduction or approved commercial usage.

