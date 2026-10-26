# ESER TECH — Data Engineering, Enrichment & Customer Intelligence

GitBook page ID: `kwqepS3R0Rh4vaqw4thG` · existing word count 7215 · staged candidate count 9115 · target **20,000+** (NOT YET MET)

This document contains the **new appendix** staged in GitBook draft change request #3, not the original existing chapter text.

### Research Goldmine expansion — service 20 (draft, 26 October 2026)

**Research classification:** This additional service-specific evaluation is not a delivered client project, not a production test, and not founder acceptance. It preserves the professional-service-versus-future-SaaS distinction. Only documented evidence may be used as an observation; video creator claims remain unverified until ESER reproduces them.

#### Evidence-backed opportunity designs

**Scenario 1: product catalog feed normalization for a small retailer.** Start with a written discovery interview identifying beneficiary roles, authority to access assets, failure cost, budget and acceptance approver. Narrow the pilot to one measurable result, provide a working demonstration or sample deliverable, and record what the client actually accepted. Avoid converting a hypothetical scenario into a false claim of ESER past work.

**Scenario 2: company directory deduplication with provenance.** Start with a written discovery interview identifying beneficiary roles, authority to access assets, failure cost, budget and acceptance approver. Narrow the pilot to one measurable result, provide a working demonstration or sample deliverable, and record what the client actually accepted. Avoid converting a hypothetical scenario into a false claim of ESER past work.

**Scenario 3: reporting pipeline from ERP exports to dashboard.** Start with a written discovery interview identifying beneficiary roles, authority to access assets, failure cost, budget and acceptance approver. Narrow the pilot to one measurable result, provide a working demonstration or sample deliverable, and record what the client actually accepted. Avoid converting a hypothetical scenario into a false claim of ESER past work.

**Scenario 4: customer segmentation from consented transactions.** Start with a written discovery interview identifying beneficiary roles, authority to access assets, failure cost, budget and acceptance approver. Narrow the pilot to one measurable result, provide a working demonstration or sample deliverable, and record what the client actually accepted. Avoid converting a hypothetical scenario into a false claim of ESER past work.

#### Deliverable packages and boundaries

- **Package 1:** source contracts and schema version record. Record source inputs, creator or vendor rights, review owner, dependency on external accounts, a priced or separately billable scope assumption, the acceptance artifact and the client handoff owner. Do not include ongoing subscriptions silently within a fixed project fee.
- **Package 2:** transform definitions and data quality rules. Record source inputs, creator or vendor rights, review owner, dependency on external accounts, a priced or separately billable scope assumption, the acceptance artifact and the client handoff owner. Do not include ongoing subscriptions silently within a fixed project fee.
- **Package 3:** PII classification, retention and deletion controls. Record source inputs, creator or vendor rights, review owner, dependency on external accounts, a priced or separately billable scope assumption, the acceptance artifact and the client handoff owner. Do not include ongoing subscriptions silently within a fixed project fee.
- **Package 4:** failure reprocessing queue with end-to-end lineage. Record source inputs, creator or vendor rights, review owner, dependency on external accounts, a priced or separately billable scope assumption, the acceptance artifact and the client handoff owner. Do not include ongoing subscriptions silently within a fixed project fee.

#### Open-source and free-tier research options

- **Crawl4AI:** [reference/source](https://github.com/unclecode/crawl4ai). Apache-2.0; publicly available lawful data. This is an evaluated candidate rather than approved deployment. Before claiming “free,” confirm exact code license, hosted billing, model inference fees, trademark/media rights, scaling limits, maintenance responsibility and data processing terms.
- **Crawlee:** [reference/source](https://github.com/apify/crawlee). Apache-2.0 queue and crawl orchestration. This is an evaluated candidate rather than approved deployment. Before claiming “free,” confirm exact code license, hosted billing, model inference fees, trademark/media rights, scaling limits, maintenance responsibility and data processing terms.
- **Supabase:** [reference/source](https://github.com/supabase/supabase). Postgres/RLS; processing and hosting costs separate. This is an evaluated candidate rather than approved deployment. Before claiming “free,” confirm exact code license, hosted billing, model inference fees, trademark/media rights, scaling limits, maintenance responsibility and data processing terms.
- **Firecrawl:** [reference/source](https://github.com/firecrawl/firecrawl). AGPL-3.0 with specific network-use obligations. This is an evaluated candidate rather than approved deployment. Before claiming “free,” confirm exact code license, hosted billing, model inference fees, trademark/media rights, scaling limits, maintenance responsibility and data processing terms.

#### Reproducible acceptance and QA test cases

- **Test 1 — idempotent reprocessing yields same records.** Specify setup and test input, expected observable output, pass/fail threshold, evidence screenshot or log, designated test operator, and remediation procedure. Run both successful and negative-path tests in a nonproduction environment where possible. A video or vendor landing page alone does not prove this ESER capability works.
- **Test 2 — schema-breaking source change raises alert.** Specify setup and test input, expected observable output, pass/fail threshold, evidence screenshot or log, designated test operator, and remediation procedure. Run both successful and negative-path tests in a nonproduction environment where possible. A video or vendor landing page alone does not prove this ESER capability works.
- **Test 3 — PII deletion propagates to derived tables.** Specify setup and test input, expected observable output, pass/fail threshold, evidence screenshot or log, designated test operator, and remediation procedure. Run both successful and negative-path tests in a nonproduction environment where possible. A video or vendor landing page alone does not prove this ESER capability works.
- **Test 4 — enrichment source is lawful and timestamped.** Specify setup and test input, expected observable output, pass/fail threshold, evidence screenshot or log, designated test operator, and remediation procedure. Run both successful and negative-path tests in a nonproduction environment where possible. A video or vendor landing page alone does not prove this ESER capability works.
- **Test 5 — sampled output matches source truth before activation.** Specify setup and test input, expected observable output, pass/fail threshold, evidence screenshot or log, designated test operator, and remediation procedure. Run both successful and negative-path tests in a nonproduction environment where possible. A video or vendor landing page alone does not prove this ESER capability works.

#### Cost, commercial, rights and security risk register

- **Risk 1: using scraped or purchased data without rights.** Record the owner of this risk, likelihood and impact, contractual control, evidence of tool/license compatibility, incident escalation route, and minimum mitigation required before accepting client funds. Do not use blanket 'free forever' or 'guaranteed' language.
- **Risk 2: excessive retention and security exposure.** Record the owner of this risk, likelihood and impact, contractual control, evidence of tool/license compatibility, incident escalation route, and minimum mitigation required before accepting client funds. Do not use blanket 'free forever' or 'guaranteed' language.
- **Risk 3: silent schema drift.** Record the owner of this risk, likelihood and impact, contractual control, evidence of tool/license compatibility, incident escalation route, and minimum mitigation required before accepting client funds. Do not use blanket 'free forever' or 'guaranteed' language.

#### Practical client-outcome measurements

- **Metric 1: valid record percentage.** Capture a baseline, the source system, reporting frequency, data ownership, exclusion conditions and a realistic target only after the client supplies history. Distinguish an ESER-delivered artifact from a business outcome driven by factors ESER does not control.
- **Metric 2: freshness against promised window.** Capture a baseline, the source system, reporting frequency, data ownership, exclusion conditions and a realistic target only after the client supplies history. Distinguish an ESER-delivered artifact from a business outcome driven by factors ESER does not control.
- **Metric 3: pipeline recovery time.** Capture a baseline, the source system, reporting frequency, data ownership, exclusion conditions and a realistic target only after the client supplies history. Distinguish an ESER-delivered artifact from a business outcome driven by factors ESER does not control.

#### Video reference queue (source research, not independently reproduced code)

- **Candidate 1:** [Crawl4AI — local, open-source web crawling that outputs LLM-ready data](https://www.facebook.com/share/r/1DwAptZnFH/) — registry tier `TIER_6_LOCAL_MP4_AND_DOSSIER_AUDIT`; uploader/creator label: Brody. Evaluate original frames/transcript, validate any code, terms and commercial claims, then accept or reject applicability for this service.
- **Candidate 2:** [420K views · 291K reactions | The client you're closest to is usually the one quietly costing you the mos](https://www.facebook.com/share/r/1cMBkzByKv/) — registry tier `TIER_2_TECHNICAL_EXTRACT`; uploader/creator label: Prime Brains. Evaluate original frames/transcript, validate any code, terms and commercial claims, then accept or reject applicability for this service.
- **Candidate 3:** [41K views · 586 reactions | 🚀 This GitHub repo could be a GAME CHANGER for vibe coders & developers. 🤯 ](https://www.facebook.com/reel/2129755597979739/) — registry tier `TIER_2_TECHNICAL_EXTRACT`; uploader/creator label: Saurabh Srivastava. Evaluate original frames/transcript, validate any code, terms and commercial claims, then accept or reject applicability for this service.
- **Candidate 4:** [49K views · 502 reactions | Someone built an AI that can make an entire YouTube video by itself 🤯 You gi](https://www.facebook.com/share/r/1GpC8EXVRS/) — registry tier `TIER_2_TECHNICAL_EXTRACT`; uploader/creator label: Sebastian Dziura. Evaluate original frames/transcript, validate any code, terms and commercial claims, then accept or reject applicability for this service.
- **Candidate 5:** [5.5K views · 6.7K reactions | Your website isn’t real until it’s deployed. Stop fighting localhost and la](https://www.facebook.com/share/r/1J71ZHYez6/) — registry tier `TIER_2_TECHNICAL_EXTRACT`; uploader/creator label: PeterCode Lab. Evaluate original frames/transcript, validate any code, terms and commercial claims, then accept or reject applicability for this service.
- **Candidate 6:** [65K views · 7.8K reactions | AI writes the code. AI reviews the code. You make the call. The pipeline tha](https://www.facebook.com/share/v/1EiQUYLyxb/) — registry tier `TIER_2_TECHNICAL_EXTRACT`; uploader/creator label: The Faction Group LLC. Evaluate original frames/transcript, validate any code, terms and commercial claims, then accept or reject applicability for this service.
- **Candidate 7:** [3.8K views · 38 reactions | ✍🏼 Drop "Link" in the comments and I'll send you the link to the prompts for](https://www.facebook.com/share/r/1JGBW3Nj2K/) — registry tier `TIER_3_MEDIA_TRANSCRIPT_QA`; uploader/creator label: 3.8K views &#xb7; 38 reactions | &#x270d;&#x1f3fc; Drop &quot;Link&quot; in the comments and I&#039;ll send you the link to the prompts for this website

Nobody remembers a website. They remember one moment on it. The scroll where the scene reacted, the transition that caught them off guard, the two seconds they stopped and thought &quot;wait, how did they do that.&quot; The rest of the page is just the frame around that moment.

Designers spend most of their time on the frame. Making everything correct, consistent, clean &#x2014; the parts that should be right but were never going to be memorable. It&#039;s necessary work, but it&#039;s the work that gets forgotten the instant someone closes the tab.

The moment is different. It&#039;s the one thing that survives the visit, gets screenshotted, gets sent to a friend, becomes the reason they remember you at all. It&#039;s a tiny fraction of the page carrying almost all of its impact &#x2014; and it&#039;s exactly the part most projects run out of time to make.

AI doesn&#039;t reward the frame. It rewards the moment people carry with them.

That&#039;s the whole idea behind our project library. The frame is handled so you can build the moment &#x2014; you start from a 3D scene and animations that already work, and spend your time on the part people remember. Production-ready, not &quot;good enough.&quot;

How it works:

1. Log into the platform.

2. Copy a highly refined prompt&#x2014;think of it as a strict filter that cuts out 99% of useless AI garbage.

3. Get the working 3D framework or interaction 1:1.

4. Refine the details to fit your project&#x2014;saving you days of endless, aimless prompt tweaking.

&#x1f4e9; DM me &quot;Project&quot; to collaborate.

#webdesign #threejs #3dwebsite #claudecode #getlayersai | Textura Agency / Design &amp; Development. Evaluate original frames/transcript, validate any code, terms and commercial claims, then accept or reject applicability for this service.

**Relevant source baseline:** [original ESER TECH live documentation](https://eser-tech.gitbook.io/eser-tech-locked-business-plan/); [cross-PC evidence reconciliation](https://github.com/dopefoxes/dopefoxes/blob/main/reviews/ESER_TECH_VIDEO_EVIDENCE_RECONCILIATION_2026-10-26.md). The 290 Aman additional clips are outside V6; 118 status flags conflict with dossier labels. Video metadata does not imply technique reproduction or approved commercial usage.

