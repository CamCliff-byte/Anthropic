# Hosting, distribution and uptake data for QTWAV's Rise 360 modules (checked 28 October 2026)

Currency: vendor prices are in USD unless stated. AUD conversions use the ATO September 2026 monthly average of A$1 = US$0.7126, so US$1 ≈ A$1.40. I got that rate through Perplexity's summary of the ATO table at https://www.ato.gov.au/tax-rates-and-codes/foreign-exchange-rates-monthly-2027-financial-year and did not open the page myself. Conversions exclude GST and card or FX fees.

## 1. Articulate 360 in 2025–2026: Rise 360 / Reach 360 sharing, learner limits, reporting, and new LMS-distribution features

### Takeaway
Articulate 360 includes three distribution routes at no extra cost:
- **Quick Share**: a public Rise link with no login, an optional guestbook, an optional password, and since October 2026 an analytics dashboard and a Survey block.
- **Reach Starter**: a login-based LMS for 300 active learners per year, on Teams seats only.
- **Connected Packages**: a Labs feature from mid-2026. It is a SCORM 1.2/2004 package that a client loads into their own LMS once. The content stays hosted by Articulate, so Capyble can push updates without re-uploading.

Connected Packages does not provide any documented central tracking across client LMSs; tracking stays in each client's LMS. Articulate has no "Dispatch"-style product that sends courses to other LMSs and reports back centrally. All three routes stop working once the subscription that owns the content lapses.

### Cited Findings
**Plans and prices (articulate.com pricing page, checked 28 Oct 2026)**
- The plans are now branded "Articulate 360 AI":
  - Teams (L&D teams): **US$1,749 per seat per year** (≈A$2,455). Includes "Reach with 300 active learners per year".
  - Single-seat plan for instructional designers: **US$1,449 per seat per year** (≈A$2,035), non-transferable.
  - Frontline: from US$500 per year, includes no Rise.
  — [Articulate pricing](https://www.articulate.com/360/pricing/)
- **Reach 360 Pro starts at US$3,600 per year for 1,200 active learners** (≈A$5,050). No per-learner add-on price is published. — [Articulate pricing](https://www.articulate.com/360/pricing/)
- The pricing page lists LMS publishing (SCORM, xAPI, cmi5) and Reach as included in 360 AI (Teams). It says analytics apply "when you use integrated distribution tools." It mentions no nonprofit discount. — [Articulate pricing](https://www.articulate.com/360/pricing/)

**Quick Share**
- Articulate's FAQ (dated May 2026, updated October 2026) says "Anyone with the link can access the training directly in a browser, with no login, no account, and no system access required." Other features:
  - Access can optionally be protected with a password.
  - A per-course dashboard tracks views.
  - When the guestbook is enabled, it captures learner names and emails on completion.
  — [Articulate FAQ](https://www.articulate.com/faq/)
- Articulate staff on the community forum say Quick Share links are public. Recipients need no subscription, and credentials are only asked for if the guestbook is on. — [E-Learning Heroes thread](https://community.articulate.com/discussions/discuss/preparing-for-quick-share/1239873/replies/1240030)
- The October 2026 "What's New" page lists:
  - a **built-in analytics dashboard** for Quick Share content covering "sessions, completions, sentiment, and time invested";
  - a **Survey block** that lets creators "add a survey to training distributed with QuickShare links", with AI-generated response summaries.
  — [Articulate What's New](https://www.articulate.com/360/whats-new/)
- The "Trackable distribution" page says Quick Share and Reach are included in "every Articulate 360 subscription" and that both feed one analytics view. — [Articulate trackable distribution](https://www.articulate.com/features/trackable-distribution/)
- **No view cap on Quick Share was found** in any source.

**Reach 360**
- Reach Starter is included with every Teams subscription and covers 300 active learners per year. Above that, you buy Reach 360 Pro, and upgrading resets the active-learner count. — [Articulate support, via search summary](https://community.articulate.com/articles/reach-360-view-active-learner-usage-reports); [Reach 360 Starter announcement](https://community.articulate.com/blog/articles/new-in-articulate-360-share-and-track-courses-with-the-reach-360-starter-plan/1153031)
- **How active learners are counted:** a learner counts when they start the first lesson of a course within a 30-day window. Viewing a course summary does not count, and completion is not required. A learner who comes back in a later 30-day period without finishing counts again. — [Reach 360 active learner usage reports](https://community.articulate.com/articles/reach-360-view-active-learner-usage-reports)
- Learners register through SSO, a QR code, a link, or a bulk CSV upload. Admins "export reports as CSV files with one click." Reach integrates with Slack, Teams, Zapier and an API, and supports a custom domain and branding. — [Articulate Reach](https://www.articulate.com/360/reach/)
- Reach 360 version history for 2025–2026:
  - Feb 2025: self-registration links for groups.
  - Mar 2025: reports show whether a learner "enrolled themselves".
  - May 2025: manual entry of quiz scores and completion dates.
  - Aug 2025: custom email domain.
  - Jun 2026: DKIM fix.
  - No entries cover anonymous or guest learners or sending courses to other LMSs.
  — [Reach 360 Version History](https://www.articulatesupport.com/article/Reach-360-Version-History)
- An older Articulate support result, relayed through Perplexity, says Reach training is not public and does not support anonymous or guestbook learners; every learner must be a member of the Reach team. I could not confirm this is still true in 2026. — [Articulate support (via Perplexity)](https://access.articulate.com/support/article/Articulate-Online-End-of-Life-Transition-Guide)

**Connected Packages ("Rise's new features" for SCORM links)**
- What it is: a Rise 360 Labs feature. You export a SCORM 1.2 or SCORM 2004 package, upload it to the LMS once, and then "push future edits directly from Rise 360". Learners see the latest version through the same LMS link, and an optional "Notify learners" banner can announce changes. — [MicroWay (AU Articulate reseller), 2 July 2026](https://www.microway.com.au/blog/articulate-connected-packages-new-lab-feature/); [E-Learning Heroes announcement](https://community.articulate.com/blog/articles/say-goodbye-to-re-uploads-update-your-lms-content-directly-from-rise-360-with-co/1262708) (returned 403 to my fetch; the search snippet confirms SCORM 1.2/2004 and Rise-only)
- MicroWay notes these caveats:
  - "Connected Package content is hosted on Articulate systems", so Australian and New Zealand organisations should run it through data, procurement and compliance review.
  - It is a LABS feature that "may change before full production release".
  - Only content owners and collaborator managers can push updates.
  - Updates may not create a new version record in the LMS.
  - It "may not be suitable for content requiring strict audit trails".
  - Teams should avoid "permanently deleting the source Rise 360 content" or disabling LABS, as this "may affect connected LMS training".
  — [MicroWay](https://www.microway.com.au/blog/articulate-connected-packages-new-lab-feature/)
- Community reports of problems with Connected Packages:
  - learners who started before a republish got "page not found" on resume;
  - the exit link failed in SuccessFactors with SCORM 2004;
  - users are asking about xAPI support.
  — [Republish issue thread](https://community.articulate.com/discussions/discuss/rise-360-connected-package-not-working-for-learners-after-republishing/1268177); [Need help thread](https://community.articulate.com/discussions/discuss/need-help-on-connected-packages/1269609); [xAPI question](https://community.articulate.com/discussions/labs/plans-to-expand-connected-packages-to-xapi/1266103)
- The October 2026 What's New page also lists a direct publish-to-Thinkific integration. — [Articulate What's New](https://www.articulate.com/360/whats-new/)

**What happens when a subscription ends**
- Articulate FAQ: "access to the authoring tools and cloud services ends." Exported courses hosted in an LMS or on the web keep running, but editing and republishing them "requires an active subscription." The FAQ does not say what happens to Quick Share or Reach. — [Articulate FAQ](https://www.articulate.com/faq/)
- Staff replies on the community forum (some years old):
  - Share links stay live while the subscription is active.
  - Content is kept for at least six months after a lapse.
  - Quick Share links stop working when the licence ends, and content is permanently deleted after six months.
  — [Share link thread](https://community.articulate.com/discussions/discuss/share-link/560189/replies/560190); [Preview link expiry thread](https://community.articulate.com/discussions/rise-360/does-a-rise-preview-link-ever-expire); [Links to modules thread](https://community.articulate.com/discussions/discuss/articulate-links-to-modules/1264733) (403 to my fetch; content from search summary)

### Inferences
- **Quick Share is the cheapest public link.** It meets need (1) at no extra cost. With the guestbook switched off and a Survey block added (for example "What type of organisation are you from?"), it gives anonymous sessions, completions and self-reported organisation type, which partly meets need (3).
  - **Risk:** the link lives on whoever owns the Rise course. If that is Capyble, the link depends on Capyble keeping its licence and dies after a lapse, which complicates need (4).
- **Reach Starter suits a known, registered cohort, not the public.** Learners need accounts, and 300 active learners per year could be used up by a sector-wide rollout. Because a returning learner can be counted again in a later 30-day window, the real capacity may be below 300 people.
  - Reach is only available if Capyble holds a **Teams** seat. The single instructional-designer seat does not list Reach.
- **Connected Packages is probably the "new feature" Cam meant.** It serves need (2) well: one SCORM file per organisation, and Capyble can update content centrally. It does **not** give QTWAV central uptake data. Each LMS keeps its own records.
  - Because content is served from Capyble's Articulate account, every client LMS copy **breaks if Capyble's subscription lapses or the course is deleted**. That works against the handover goal unless QTWAV or a sector host takes on its own Articulate seat.
  - It is a Labs (beta) feature, so it is risky to promise it to funders.
- For a durable LMS package that does not depend on any subscription, give organisations a **standard SCORM 1.2 export**. It keeps working indefinitely in their LMS.

### Gaps
- No official statement on whether Quick Share links survive a subscription lapse, or on any view limit. The only evidence is old forum replies; ask Articulate in writing.
- Not confirmed:
  - whether the Quick Share analytics dashboard data or guestbook entries can be exported as CSV;
  - whether the Survey block's results can be exported.
- Not confirmed whether Reach 360 supports custom registration fields such as organisation type in 2026 (2024 history mentions custom fields).
- No documentation on whether Articulate collects any cross-LMS launch data from Connected Packages, or what happens to them after a lapse.
- No AUD pricing for Articulate or Reach Pro was available (US prices only). Whether Capyble holds a Teams seat or the single seat is unknown and determines whether Reach is available.

## 2. SCORM dispatch tools (Rustici SCORM Cloud Dispatch and others)

### Takeaway
SCORM Cloud is the one low-cost, off-the-shelf way to provide a **public link and LMS packages from one central place with one dataset**:
- Public Invitation links serve the public.
- Dispatch packages go to organisations that have an LMS.

It is priced per learner-course registration in rolling 30-day windows. The "Little" plan is **US$90 per month (≈A$1,515 per year)**, which uses almost exactly the A$1,500 budget, with 50 registrations a month and overage that can be capped. It is US-hosted. No nonprofit discount is published.

### Cited Findings
- SCORM Cloud plans (USD per month, excluding tax; registrations per 30 days; overage per registration):

  | Plan | Price | Registrations | Overage |
  |---|---|---|---|
  | Trial | free | 3 courses / 5 GB, 10 resettable | — |
  | Tester | $40 | 10 resettable | — |
  | Little | $90 | 50 | $3.60 |
  | Medium | $180 | 100 | $3.60 |
  | Big | $360 | 300 | $0.40 |
  | Bigger | $1,100 | 4,000 | $0.25 |
  | Mega | $2,000 | 10,000 | $0.12 |
  | Ultra | $5,000 | 50,000 | $0.10 |

  The trial "isn't time-based". No nonprofit discount is mentioned. — [SCORM Cloud pricing](https://rusticisoftware.com/products/scorm-cloud/pricing/)
- "All paid tiers of SCORM Cloud come with the full functionality of the application." Public invitations "generate a public link that you can post anywhere", and private invitations go out by email. "Each SCORM Cloud account comes with an LRS." Out-of-the-box reports are included. — [SCORM Cloud product page](https://rusticisoftware.com/products/scorm-cloud/)
- How Dispatch works (Perplexity summary of Rustici pages, not checked line by line):
  - It produces a lightweight shell package that the client imports into a SCORM 1.2 or LTI-capable LMS, and the shell launches the course hosted centrally in SCORM Cloud.
  - Usage data is consolidated in SCORM Cloud.
  - Each dispatch can be switched on or off and can have user limits and expiry dates.
  - A registration is created on a learner's first launch of a course and is charged once, in the month it is created.
  - Overages can be disabled.
  — [Rustici Dispatch](https://rusticisoftware.com/products/rustici-dispatch/); [What's a registration](https://support.scorm.com/hc/en-us/articles/206163476-Getting-Started-What-s-a-Registration); [SCORM Cloud pricing](https://rusticisoftware.com/products/scorm-cloud/pricing/)
- Alternatives (Perplexity summary):
  - Rustici Content Controller, LearnUpon, Elucidat and Xyleme are quote-based, enterprise-oriented tools.
  - SmartBuilder is an authoring tool (US$1,399 per year, or US$1,299 for nonprofits), not a dispatch service.
  — [SmartBuilder pricing](https://www.smartbuilder.com/product/pricing/); [Rustici Content Controller](https://rusticisoftware.com/solutions/content-providers/)

### Inferences
- **Volume check.** Two modules × (say) 300 learners over two years is about 600 registrations, or about 25 a month on average. That fits "Little" (50 per month) if uptake is spread out. A launch spike (for example 150 people in the first month, each taking two modules) would mean overage of up to (300 − 50) × US$3.60 = **US$900**, unless overages are disabled or the plan is upgraded temporarily to Big (US$360) for launch months. Recommend disabling overage and watching the counts.
- **Tester (US$40 per month)** allows only 10 resettable registrations, so it suits testing only, not production.
- **Strengths:** one dataset covers the public and every LMS; QTWAV can turn off a dispatch; it does not depend on Capyble's Articulate licence. Rise SCORM uploads to SCORM Cloud work as standard.
- **Weaknesses:** it is US-hosted (see section 4). Public invitations typically ask for name and email, which I could not confirm. The learner interface is basic.
- **Alternative:** a lower-cost hybrid of Quick Share plus plain SCORM files (no Cloud) keeps SCORM Cloud as an optional extra.

### Gaps
- Not verified on Rustici's own pages:
  - whether public invitations require name and email or can be anonymous;
  - which data fields reports export;
  - data residency options.
- No published nonprofit or education discount. Ask Rustici for a quote (and about GST and AUD invoicing).
- Dispatch's LTI and SCORM 2004 support and the "Dispatch included in all plans" claim come from Perplexity, not my own page read.

## 3. Alternative low-cost options: web export on a website, xAPI/LRS, low-cost LMSs

### Takeaway
- A Rise **Web export** hosted on QTWAV's or a partner's website is free, public and does not depend on any subscription. It is the best long-term "outlasts the funding" copy, but it gives only page-level analytics if you add something like Plausible or Google Analytics.
- xAPI to a free LRS is technically possible but needs developer-level launch configuration.
- Small-NFP LMSs (TalentLMS, MoodleCloud, LearnDash) all require logins and cost more than the options above for this use.

### Cited Findings
- A Rise Web export does not provide LMS-style completion or learner records by itself. GA, Tag Manager or Plausible scripts can be added through the site wrapper or hosting layer, but they measure visits and events, not learning records. — Perplexity synthesis, no primary source cited; treat as expert inference.
- For a plain web-hosted package to send xAPI to an LRS, you need an endpoint, credentials and a launch mechanism that supplies them. "Hosted on a website" and "sending xAPI to an LRS" are separate requirements. Free LRS options include the SCORM Cloud LRS, Veracity's free tier (limits unverified), and self-hosted open-source LRSs (Learning Locker, Yet Analytics SQL LRS). — Perplexity synthesis; [SCORM Cloud product page](https://rusticisoftware.com/products/scorm-cloud/) (LRS included)
- TalentLMS:
  - Free plan: up to 5 active users and 10 courses.
  - Core shown at US$119 per month for a 1–40 user band.
  - Grow: US$299 per month, or US$2,748 per year for 1–70 users.
  - Registered nonprofits get **20% off annual plans**.
  — [TalentLMS prices](https://www.talentlms.com/prices); [TalentLMS non-profit](https://www.talentlms.com/industries/non-profit); [TalentLMS help](https://help.talentlms.com/hc/en-us/articles/9652350605468-How-to-start-a-subscription-to-TalentLMS)
- MoodleCloud bills in AUD, and a custom domain on Medium plans costs an extra A$160 per year. Current Starter and Mini prices could not be retrieved. — [MoodleCloud plans overview](https://support.moodle.com/support/solutions/articles/80000833221-moodlecloud-plans-overview); [MoodleCloud](https://moodle.com/products/moodlecloud/)
- Articulate FAQ: courses exported and hosted on the web or in an LMS keep running after the subscription ends. — [Articulate FAQ](https://www.articulate.com/faq/)

### Inferences
- **Recommended belt-and-braces approach:** publish a Rise Web export to a QTWAV-controlled (or long-lived partner) web host as the permanent public copy, with privacy-friendly page analytics (Plausible or a cookieless GA setup). Each Rise lesson is a URL hash route, so lesson-level page-view events may need configuration; this is unverified.
- TalentLMS free (5 users) is unusable at this scale. Paid TalentLMS (about US$2,200 per year after the nonprofit discount on Grow) is above budget and requires logins.
- MoodleCloud could be cheap, but it requires logins and admin effort. That conflicts with 1–2 hours a month of maintenance and with anonymous public access.

### Gaps
- No verified current prices for LearnDash, MoodleCloud Starter or Mini, or Plausible.
- No verified Veracity LRS free-tier limits.
- Not tested whether Rise Web exports allow analytics script injection without editing exported files.
- **Not researched:** whether Queenslanders with Disabilities Network (QDN), QC, DVConnect or a sector peak (for example a DFV peak body) offers hosting. This is worth asking.

## 4. Realistic, privacy-appropriate uptake data; APPs and QPPs; funder evidence

### Takeaway
Collect **anonymous, aggregate** data by default:
- starts, completions and time from Quick Share or SCORM Cloud;
- a self-reported "organisation type / role / region" survey question with no names;
- optional named certificates only where an organisation asks for them.

QTWAV is probably exempt from the Privacy Act as a small (under A$3m turnover) unincorporated body. However, its Queensland government funding agreement may bind it to the Queensland Privacy Principles (in force from 1 July 2025), including the overseas-disclosure rule in section 33, which matters for US-hosted SCORM Cloud or Articulate. Check the funding agreement.

### Cited Findings
- Privacy Act s6D small business exemption: annual turnover of $3m or less is exempt, except for health service providers holding health information, traders in personal information, and contracted service providers under a Commonwealth contract. — Perplexity synthesis of OAIC and Attorney-General's material; s6D is well established
- As of October 2026, the tranche 2 reforms had not removed the small business exemption. They had only been announced or proposed. — [AG press conference transcript, 31 Aug 2026 (via Perplexity)](https://ministers.ag.gov.au/media-centre/transcripts/press-conference-blue-room-31-08-2026) (not opened directly; verify)
- The Queensland Privacy Principles apply from 1 July 2025 under the Information Privacy and Other Legislation Amendment Act 2023. Agencies must take reasonable steps to bind contracted service providers that deal with personal information for the agency.
  - Exception: a provider that merely receives funding and does not collect personal information for the agency, give it to the agency, or receive it from the agency.
  - Bound contractors must also comply with s33 (overseas disclosure).
  — [OIC: contractors and privacy](https://www.oic.qld.gov.au/government/privacy/contractors-privacy); [OIC: QPPs](https://www.oic.qld.gov.au/government/privacy/queensland-privacy-principles)
- OIC on cloud hosting: if overseas servers are used and the agency loses control of the information, the transfer may be an overseas disclosure under s33. If the provider can use the data for its own purposes, it is more likely to be a disclosure. — [OIC: privacy and technology](https://www.oic.qld.gov.au/government/privacy/privacy-technology)
- Properly de-identified or aggregated statistical data falls outside the QPPs, but de-identification must be effective. Small cohorts and unique roles create re-identification risk. — [OIC: data analytics](https://www.oic.qld.gov.au/guidelines/for-government/guidelines-privacy-principles/use-and-disclosure/data-analytics)
- QPP 2 / APP 2: individuals should be able to deal anonymously or under a pseudonym where practicable. — [OIC: QPPs](https://www.oic.qld.gov.au/government/privacy/queensland-privacy-principles)

### Inferences
- **Realistic dataset for the funder:**
  - number of unique sessions and starts, and completions per module (Quick Share dashboard or SCORM Cloud);
  - completion rate;
  - counts by self-reported organisation type, role (board / manager / staff) and region from an anonymous survey;
  - aggregate post-module confidence or intent-to-act ratings (the Survey block);
  - the number of organisations that took the SCORM package (a simple request form or log);
  - LMS-reported completion counts that organisations voluntarily send back each quarter.
- Avoid individual quiz scores tied to names. Report only aggregates, and suppress small cells (for example under 5), which matters for a small queer and trans workforce where re-identification risk is high.
- **Sensitivity:** questions about LGBTIQ+ identity are sensitive information. Do **not** ask about learners' own sexuality or gender identity in uptake forms.
- **Guestbook:** switching the Quick Share guestbook on means collecting identified names and emails on Articulate's (US) systems. Keep it off unless certificates are needed, and if used, give a collection notice.
- **What funders accept (inference; not researched):** Queensland DFV funders typically accept aggregate output counts (reach and completions) plus a short outcome measure (pre/post confidence). Platform-generated counts plus survey summaries are normally adequate evidence.

### Gaps
- I did not find Queensland DFV funder reporting templates or DJAG/DCSSDS evidence requirements. I could not confirm what QTWAV's funder specifically requires.
- I could not confirm whether QTWAV's funding agreement binds it to the QPPs; this needs a check of the agreement.
- Articulate and Rustici data residency (US versus AU regions) not verified.
- The tranche 2 status comes from a Perplexity-relayed source that I did not open.

## 5. Ownership and handover: account holder, source files, link behaviour on lapse

### Takeaway
Anything served from Capyble's Articulate account dies when Capyble's subscription lapses: Quick Share, Reach, and every client copy of a Connected Package. Anything exported (a Web package, standard SCORM files) or hosted on a QTWAV-owned account (for example SCORM Cloud) survives.

Handover plan:
- QTWAV, or a successor or partner organisation, owns the hosting account (SCORM Cloud and/or the web host) from day one, with Capyble as a delegated admin.
- Capyble delivers, at end of term:
  - final standard SCORM 1.2 and Web exports;
  - video masters and caption files;
  - an archived copy of the Rise course passed to any Articulate 360 holder QTWAV nominates.

### Cited Findings
- After a subscription ends, cloud services end. Exported courses in an LMS or web environment keep working, but editing or republishing them requires a subscription. — [Articulate FAQ](https://www.articulate.com/faq/)
- Quick Share links stop working when the licence ends, and content is retained for at least six months before deletion (community staff replies; not an official policy page). — [Preview link expiry thread](https://community.articulate.com/discussions/rise-360/does-a-rise-preview-link-ever-expire); [Links to modules thread](https://community.articulate.com/discussions/discuss/articulate-links-to-modules/1264733)
- Connected Packages break if the Rise source is permanently deleted or LABS is disabled. Restoring them means uploading a standard package by hand. — [MicroWay](https://www.microway.com.au/blog/articulate-connected-packages-new-lab-feature/); search summary of [E-Learning Heroes announcement](https://community.articulate.com/blog/articles/say-goodbye-to-re-uploads-update-your-lms-content-directly-from-rise-360-with-co/1262708)
- SCORM Cloud Dispatch can be switched off or expired per destination by the account holder. — [Rustici Dispatch](https://rusticisoftware.com/products/rustici-dispatch/) (via Perplexity)
- The Articulate 360 single seat is "non-transferable". — [Articulate pricing](https://www.articulate.com/360/pricing/)

### Inferences
- **Two-year (Capyble-hosted) phase:** Quick Share (or SCORM Cloud) for the public link, SCORM packages for LMS organisations, and a quarterly uptake report to QTWAV.
- **Before October 2027:**
  1. Hand QTWAV standard SCORM 1.2 and Web zip exports of the final versions.
  2. Re-issue standard (not Connected) SCORM packages to any organisation using Connected Packages.
  3. Move the public copy to a QTWAV-controlled or partner web host, and point a QTWAV-owned short domain or URL at it from day one, so the public link never changes when hosting moves.
  4. Transfer the SCORM Cloud account (if used) or export its reports as CSV.
  5. Provide the Rise source either by sharing or duplicating it to a nominated Articulate 360 user or by keeping an archived copy at Capyble under a licence agreement.
  6. Provide video masters, SRT/VTT captions and transcripts on a QTWAV drive.
- **Contract terms:** QTWAV owns or is licensed to use the content (state IP and a Creative Commons licence if wanted). Capyble keeps the Rise source for an agreed period.

### Gaps
- Not verified with Articulate how a Rise course moves to a separate organisation's Articulate 360 account (for example "Send a copy" or sharing to an external user). Confirm before promising it.
- No official Articulate policy page on retention after a lapse; only forum replies.

## 6. Accessibility of Rise 360 output (WCAG 2.2 AA; captions)

### Takeaway
Articulate's Rise 360 Accessibility Conformance Report (VPAT 2.5 INT), dated **9 September 2026**, reports **support for every WCAG 2.2 Level A and AA criterion except 3.1.2 Language of Parts**. Captions work if the author supplies caption files or reviews the AI-generated ones. Caption appearance cannot be adjusted by the user, and there is no dedicated audio-description control.

### Cited Findings
- The report is dated September 9, 2026 (based on that build). It marks no Level A criteria as partial or unsupported. The only failing Level AA criterion is **3.1.2 Language of Parts**: Rise "does not support programmatically identifying different languages for individual passages". — [Rise 360 ACR/VPAT](https://www.articulate.com/about/accessibility/rise-360-accessibility-conformance-report-vpat/)
- 1.2.2 Captions (Prerecorded) is marked Supports: authors import caption files, and AI-assisted draft captions are available, which authors must review and edit before publishing. — [Rise 360 ACR/VPAT](https://www.articulate.com/about/accessibility/rise-360-accessibility-conformance-report-vpat/)
- 1.2.5 Audio Description is marked Supports, provided the video file contains an audio-described track. Rise "does not include a dedicated audio description control". EN 301 549 7.1.4 (caption characteristics) is marked Partially Supports because "the appearance of captions is not user-adjustable". — [Rise 360 ACR/VPAT](https://www.articulate.com/about/accessibility/rise-360-accessibility-conformance-report-vpat/)
- Many criteria "depend on authoring decisions", including custom-colour contrast (3:1 non-text). — [Rise 360 ACR/VPAT](https://www.articulate.com/about/accessibility/rise-360-accessibility-conformance-report-vpat/)
- Kennesaw State's review of an earlier (March 2026) VPAT also found 3.1.2 as the only AA failure. — [Kennesaw State VPAT summary](https://campus.kennesaw.edu/faculty-staff/academic-affairs/curriculum-instruction-assessment/digital-learning-innovations/academic-web-accessibility/advanced-accessibility-solutions/docs/vpat_summary_rise_360.pdf)

### Inferences
- Capyble can fairly say: "Built in Rise 360, whose published output Articulate reports as supporting WCAG 2.2 AA except 3.1.2 Language of Parts. Capyble will supply edited captions, transcripts, alt text and contrast-checked colours."
- Avoid passages in other languages (for example Indigenous-language words in long passages) or accept the 3.1.2 limitation.
- For video, provide burned-in or open captions as well as SRT/VTT only if caption styling matters, because caption appearance cannot be adjusted.
- Provide an audio-described or text-described version of any video that carries visual-only information.

### Gaps
- The conformance claim is Articulate's own vendor report. No independent audit of 2026 Rise output was found.
- Not verified whether captions behave the same way in Web, SCORM, Quick Share and Connected Package outputs.
