# GitLab and the framework: comparison

| Field | Value |
|---|---|
| Study ID | CS-003 |
| Practice IDs | GIT-01 to GIT-15 |
| Framework version compared | snapshot of 2026-10-12 (see `../decisions.md`) |
| Written | 2026-11-23 |
| Last updated | 2026-11-23 |
| Sources | listed under *Sources* at the end of this file (source numbers in brackets) |

Area codes, fit values and how this file feeds decisions: see `../README.md`.

## 1. Summary

GitLab **confirms** most of the framework's operating practices at the scale of a listed company with about 2,500 staff: a public handbook, a public issue tracker and direction page, public postmortems, community contributions credited in every release, and a decision reversed in public after community pushback.

It **adds** two things the framework lacks:
- an explicit, published list of what stays internal and why: financials, strategy, pricing plans, reorganisations, security;
- written promises to the community about what will always stay free and open.

It is the **cautionary case** for the framework's central bet. In May 2026 a new CEO retired "Transparency" as a company value in one memo, and the Values page was deleted from the handbook five months later. What survived were the commitments made to outsiders (stewardship promises, the open-source licence) and the habits that customers and contributors depend on (handbook, issue tracker). Lesson for FD-06 and FD-01: write the principles as commitments to customers and community, with a public record and a cost to breaking them. An internal value list can be dropped in one memo.

## 2. Overview

| ID | GitLab practice | Area | Fit | Decision topic |
|---|---|---|---|---|
| GIT-01 | Public handbook (2,000+ pages, Creative Commons): "public handbook first" | TR, CO | match | FD-03, FD-06 |
| GIT-02 | Published confidentiality levels: what is internal or limited access, and why | TR | partial | FD-03 |
| GIT-03 | Transparency as a named value, retired by the CEO in one memo (2026); Values page deleted | TR, OW | differs | FD-01, FD-03, FD-06 |
| GIT-04 | Public postmortem and livestreamed recovery of a data-loss incident (2017) | TR, CI | match | FD-03 |
| GIT-05 | Public issue tracker and direction page; community contributions credited in release notes | PD, PM | match | FD-05 |
| GIT-06 | Open core with a written rule for free vs paid: "who cares most" (individual vs manager) | PR, PD | gap | FD-04, FD-05 |
| GIT-07 | Stewardship promises to the open-source community: open features never move to paid | CO, PD | gap | FD-05, FD-06 |
| GIT-08 | Price changes explained by value added (Premium $19→$29, transition price; tier dropped for "hurdle rate") | PR | partial | FD-04 |
| GIT-09 | No cost disclosure; anything that helps construct profit is confidential | PR, TR | differs | FD-04 |
| GIT-10 | Decision reversed in public after community pushback, with a lasting commitment (2019 telemetry) | PD, CO | match | FD-05 |
| GIT-11 | Public compensation calculator, later restricted to staff and candidates, now offline | PE, TR | partial | FD-02, FD-03 |
| GIT-12 | Sensitive hiring policy debated in public (2019), but a critical resignation post redacted | PE, TR | partial | FD-02, FD-03 |
| GIT-13 | All-remote and asynchronous by default; Act 2 adds "sync for speed" | PE, PM | gap | FD-02 |
| GIT-14 | Venture funding, IPO and recurring sale talk; values changed under growth and AI pressure | OW, LT | gap | FD-01, FD-07 |
| GIT-15 | Restructuring called "transparent" while reorganisation plans are classed as limited access | PE, TR | partial | FD-02, FD-03 |

Count: 4 match, 5 partial, 4 gap, 2 differs.

## 3. Practices in detail

### GIT-01: Public handbook

- **What the company does:** more than 2,000 printed pages, open to the world, Creative Commons-licensed; "public handbook first", with a separate internal handbook for what can't be public [39].
- **Why it works for them:** all-remote company; the handbook replaces meetings and hallway knowledge. Being public also served recruiting and marketing.
- **Fit:** match with principles 1 and 4 and strategy 2 (documentation).
- **Transfer:** a small company can start with a public handbook from day one; GitLab shows it scales to thousands of people. It survived Act 2 because outsiders rely on it.

### GIT-02: Published confidentiality levels

- **What the company does:** a public page lists what is internal and what is limited access, and why [5].
  - **Internal:** financials before release, unfixed vulnerabilities, customer and legal matters, competitive plans, free-tier limit changes, strategy, patents.
  - **Limited access:** reorganisation plans, planned pricing changes, acquisition offers, compensation inputs, security investigations.
- **Fit:** partial. The framework says "all aspects" are public. GitLab shows what an honest exception list looks like at a listed company, close to the FD-03 recommendation of a short list of what stays private, with reasons.
- **Transfer:** adopt the format: a published list of exceptions with a reason for each. But keep the list short. GitLab's grew to include strategy and pricing plans, the very things the framework wants public.

### GIT-03: Transparency as a value, retired in one memo

- **What the company does:** "Transparency" was the T in CREDIT. On 2026-05-11 CEO Bill Staples wrote: "We will be retiring CREDIT as our values framework… We are not retiring them because they were wrong, we are choosing instead to focus on something different for this era which demands a different operating posture." New principles: Speed with Quality, Ownership Mindset, Customer Outcomes [1]. The Values page was deleted on 2026-10-30 [3]. The mission changed from "everyone can contribute" to "everyone can ship" [7].
- **Why it happened:** founder stepped back for health reasons (2024), new CEO from outside, listed-company growth targets, AI reorganisation, buyer speculation [1, 19, 30].
- **Fit:** differs, as an outcome. It is the scenario the framework has to guard against.
- **Candidate for explicit rejection:** principles carried only as internal values that the CEO can retire alone. What we do instead: anchor them as public commitments to customers and community (see GIT-07), in statutes or ownership (FD-01), and require a public process to change them.

### GIT-04: Public postmortem and livestreamed recovery

- **What the company does:** in 2017 the production database was deleted and backups had failed. GitLab kept public notes, livestreamed the recovery (peak about 5,000 viewers), and published a full postmortem [21].
- **Fit:** match with principle 1, like Buffer's post-mortems (BUF-13), Toyota's hansei (TOY-15) and Framework's admissions (FRM-11).
- **Transfer:** for serious incidents, work in public while it's happening, not only afterwards.

### GIT-05: Public issue tracker and direction

- **What the company does:** issues are public; the direction page lists what's coming ("Plans subject to change"); monthly release notes credit community contributions; about 1,800 community code contributions in one quarter of 2024 [19, 46].
- **Fit:** match with principles 2 and 4. Unlike Buffer's upvote board (BUF-08), the community can contribute the code itself, not just ask for it.
- **Transfer:** let the community contribute directly where the product allows it, and credit them by name.

### GIT-06: Open core with a written free-vs-paid rule

- **What the company does:** the Community Edition is MIT-licensed. A feature is paid if the buyer who "cares most" about it is a manager, and free if it's an individual contributor [6, 40].
- **Fit:** gap. The framework says nothing about what is free and what is paid. A written rule makes that decision predictable and checkable.
- **Transfer:** publish the rule that decides what is free, what is paid, and in which tier.

### GIT-07: Stewardship promises

- **What the company does:** twelve published promises, still live. Among them:
  - open-source features never move to a paid tier;
  - no delayed open-source releases;
  - no artificial limits;
  - most new features open source;
  - benchmarking allowed;
  - installation without an email address.

  They don't cover the SaaS product [6].
- **Why it works for them:** contributors and self-hosting customers rely on them, so breaking them would cost GitLab its community and customers.
- **Fit:** gap. The framework has no concept of binding promises to the community. These promises survived Act 2 while the internal values didn't.
- **Transfer:** write the core principles as public, specific promises to customers and community, with an explicit scope.

### GIT-08: Price changes explained by value added

- **What the company does:**
  - **2021:** dropped the Bronze tier because it "does not meet the hurdle rate", with transition discounts [26].
  - **2023:** raised Premium from $19 to $29, explained by 400+ features added since 2018, with a $24 price for existing customers for one year [25].
- **Fit:** partial. The changes were announced and explained with notice, but by value delivered, not by costs.
- **Transfer:** the transition price for existing customers is worth keeping, like Framework honouring pre-order prices (FRM-03).

### GIT-09: No cost disclosure

- **What the company does:** revenue and costs before release, and anything "a first step to constructing a profit", are confidential [5].
- **Fit:** differs from principle 3, like Patagonia (PAT-07) and Framework (FRM-17). As a listed company, GitLab does publish audited financials each quarter, but not costs per product or per user.
- **Candidate for rejection:** same as PAT-07.

### GIT-10: Public reversal after community pushback

- **What the company does:** on 23 October 2019 it announced third-party telemetry in its terms of service. It reversed this the next day and committed "to not implementing telemetry in our products that sends usage data to a third-party product analytics service", with a public retrospective [28].
- **Fit:** match. Community input changed a decision quickly, and the outcome was written down.
- **Transfer:** when the community pushes back, decide in public and record the result as a commitment.

### GIT-11: Compensation calculator, public then private

- **What the company does:** the pay formula was documented and iterated in public (2018). It was later limited to "team members and candidates in the pipeline" because of third-party salary data, and is now offline [38].
- **Fit:** partial. It is the same idea as Buffer's formula (BUF-03), withdrawn over time.
- **Transfer:** publish the formula and bands using your own data, so outside licences don't force it private.

### GIT-12: Sensitive hiring policy debated in public, with redaction

- **What the company does:** in 2019 it debated in public whether to stop hiring certain roles resident in China or Russia. A director resigned publicly, citing "retaliatory behavior", and GitLab redacted her post [29].
- **Fit:** partial. Open debate is a strength; redacting dissent is not.
- **Transfer:** if debates are public, critical voices should be too.

### GIT-13: All-remote and asynchronous

- **What the company does:** all-remote from early on, async by default. Act 2 now says "We use both sync (for speed) and async (for scale) patterns" [1].
- **Fit:** gap (employees and ways of working are not in the framework).

### GIT-14: Venture funding, IPO, sale talk

- **What the company does:** about $426M of venture money by 2019 (press figure), IPO in 2021, dual-class shares until August 2026, repeated reports of sale talks, values changed in 2026 [11, 23, 24, 30].
- **Fit:** gap. More evidence for FD-01: the same pattern as Everlane (EVL-08), though slower and with more of the substance kept.

### GIT-15: "Transparent" restructuring with secret plans

- **What the company does:** the 2026 cuts (about 14 %, 22 countries exited, up to three management layers removed) were announced with planning shared with staff and a voluntary separation window. Its own policy keeps reorganisation plans as limited access [1, 5].
- **Fit:** partial. Communication at the point of decision, not before.

## 4. Where the framework goes further than this company

- **Cost disclosure (principle 3):** GitLab never disclosed costs per product or user.
- **"All aspects transparent":** strategy, pricing plans and reorganisations are internal at GitLab.
- **A principle that survives a leadership change:** the framework doesn't solve this either yet. GitLab shows why it must (FD-01, FD-06).

## 5. Candidates for explicit rejection

- **GIT-03, internal values a CEO can retire alone:** reject. Anchor principles as public commitments with a public change process.
- **GIT-09, no cost disclosure:** reject, as with PAT-07 and FRM-17.
- **GIT-02, a long exception list including strategy and pricing plans:** adapt. Keep the format, shorten the list.

## 6. Open questions for the decisions

- **FD-06:** should the framework require that any change to its principles goes through a public proposal and comment period, like a handbook merge request open to outside comment?
- **FD-01:** what structure would have stopped Act 2? A stewardship promise enforceable by the community, a foundation holding the trademark, or a golden share?
- **FD-05:** does "everyone can contribute" need to be written as a commitment, not just a mission statement?

## 7. Updates

- 2026-11-23: comparison written.

## Sources

Source list from the underlying company study. Numbering matches the brackets above.

| # | Author / outlet | Title | Date | Type | Link |
|---|---|---|---|---|---|
| 1 | Bill Staples, GitLab blog | GitLab Act 2 | 2026-05-11 | primary | https://about.gitlab.com/blog/gitlab-act-2/ |
| 2 | GitLab Handbook | Operating Principles | read 2026-11-23 | primary | https://handbook.gitlab.com/handbook/company/operating-principles/ |
| 3 | GitLab Handbook | Handbook Changelog (!21784, 2026-10-30; !21886, 2026-11-02) | 2026 | primary | https://handbook.gitlab.com/handbook/about/changelog |
| 4 | GitLab Handbook | GitLab Values (cached copy, likely stale) | — | primary | https://handbook.gitlab.com/handbook/values/ |
| 5 | GitLab Handbook | Confidentiality levels | modified 2026-10-30 | primary | https://handbook.gitlab.com/handbook/communication/confidentiality-levels/ |
| 6 | GitLab Handbook | Our stewardship of GitLab | modified 2026-08-27 | primary | https://handbook.gitlab.com/handbook/company/stewardship/ |
| 7 | GitLab Handbook | Mission | modified 2026-05-13 | primary | https://handbook.gitlab.com/handbook/company/mission/ |
| 8 | GitLab Handbook | What "Ownership Mindset" means | 2026 | primary | https://handbook.gitlab.com/handbook/company/operating-principles/ownership-mindset |
| 9 | GitLab | Q1 FY27 results | 2026-06-02 | primary | https://s204.q4cdn.com/984476563/files/doc_news/GitLab-Reports-First-Quarter-Fiscal-Year-2027-Financial-Results-2026.pdf |
| 10 | GitLab (SEC Ex. 99.1) | Q2 FY27 results | 2026-09-01 | primary | https://www.sec.gov/Archives/edgar/data/1653482/000162828026059820/gitlab-ex99120260731fy27.htm |
| 11 | GitLab | Form 10-Q, quarter ended 2026-07-31 | 2026 | primary | https://www.sec.gov/Archives/edgar/data/1653482/000162828026059943/gtlb-20260731.htm |
| 12 | GitLab | Q4 and FY26 results | 2026-03-03 | primary | https://ir.gitlab.com/news/news-details/2026/GitLab-Reports-Fourth-Quarter-and-Full-Year-Fiscal-Year-2026-Financial-Results-Board-of-Directors-Authorizes-400-million-for-Share-Repurchase-Program/default.aspx |
| 13 | GitLab | Q4 and FY25 results | 2025-03 | primary | https://ir.gitlab.com/news/news-details/2025/GitLab-Reports-Fourth-Quarter-and-Full-Fiscal-Year-2025-Financial-Results/default.aspx |
| 14 | GitLab (via Yahoo) | Q4 and FY23 results | 2023-03-13 | primary | https://finance.yahoo.com/news/gitlab-reports-fourth-quarter-full-200500288.html |
| 15 | GitLab | Form 10-K FY24 | 2024 | primary | https://www.sec.gov/Archives/edgar/data/1653482/000162828024012963/gtlb-20240131.htm |
| 16 | GitLab | Form 10-K FY26 | 2026 | primary | https://www.sec.gov/Archives/edgar/data/1653482/000162828026018731/gtlb-20260131.htm |
| 17 | GitLab | To announce Q3 FY27 results | 2026-11-17 | primary | https://about.gitlab.com/press/releases/2026-11-17-gitlab-to-announce-third-quarter-fiscal-year-2027-financial-results |
| 18 | GitLab | Q2 FY27 earnings call transcript | 2026-09-01 | primary | https://s204.q4cdn.com/984476563/files/content_files/GTLB-USQ_Transcript_2026-09-01.pdf |
| 19 | Sid Sijbrandij, GitLab blog | GitLab names Bill Staples as new CEO | 2024-12-05 | primary | https://about.gitlab.com/blog/gitlab-names-bill-staples-as-new-ceo/ |
| 20 | GitLab blog | An announcement from GitLab CEO Sid Sijbrandij | 2023-02-09 | primary | https://about.gitlab.com/blog/gitlab-news |
| 21 | GitLab blog | Postmortem of database outage of January 31 | 2017-02-10 | primary | https://about.gitlab.com/blog/postmortem-of-database-outage-of-january-31 |
| 22 | GitLab Handbook; GitLab blog | History of GitLab; Letter from shareholders | 2014– | primary | https://handbook.gitlab.com/handbook/company/history |
| 23 | GitLab blog; TechCrunch | Series E funding | 2019-09-17 | primary / press | https://about.gitlab.com/blog/gitlab-series-e-funding |
| 24 | GitLab; CNBC | IPO pricing; Nasdaq debut | 2021-10-13/14 | primary / press | https://www.cnbc.com/2021/10/14/gitlab-jumps-in-nasdaq-debut-after-pricing-ipo-above-expected-range.html |
| 25 | David DeSanto, GitLab blog | New pricing for GitLab Premium | 2023-03-02 | primary | https://about.gitlab.com/blog/gitlab-premium-update |
| 26 | GitLab blog | GitLab is moving to a three-tier product subscription model | 2021-01-26 | primary | https://about.gitlab.com/blog/new-gitlab-product-subscription-model |
| 27 | GitLab | Pricing page | read 2026-11-23 | primary | https://about.gitlab.com/pricing/ |
| 28 | GitLab issue #34833; ZDNet | Telemetry update; GitLab backs down | 2019-10 | primary / press | https://gitlab.com/gitlab-org/gitlab/-/issues/34833 |
| 29 | GitLab blog; ZDNet; Business Insider | Hiring discussions; director resigns | 2019 | primary / press | https://www.businessinsider.com/gitlab-director-resigns-retaliatory-behavior-2019-11 |
| 30 | Reuters (via Yahoo); Investing.com | GitLab explores sale; Wolfe doubts Datadog deal | 2024-07-17; 2025-10 | press | https://finance.yahoo.com/news/exclusive-google-backed-software-developer-060252892.html |
| 31 | TechCrunch | GitLab cuts 14% of staff as it scales its platform to serve AI workloads | 2026-06-03 | press | https://techcrunch.com/2026/06/03/gitlab-cuts-14-of-staff-as-it-scales-its-platform-to-serve-ai-workloads |
| 32 | Times of India | GitLab cuts hundreds of jobs, exits 22 countries | 2026-06 | press | https://timesofindia.indiatimes.com/technology/tech-news/5-billion-plus-company-gitlab-cuts-hundreds-of-jobs-exits-22-countries-ceo-blames-it-on-ai-says-agentic-era-is-creating/articleshow/131496062.cms |
| 33 | Hacker News | GitLab announces workforce reduction and end of their CREDIT values | 2026-05 | opinion | https://news.ycombinator.com/item?id=48100500 |
| 34 | Glassdoor | Working at GitLab | 2026-11 | opinion (aggregate) | https://www.glassdoor.com/Overview/Working-at-GitLab-EI_IE1296544.11,17.htm |
| 35 | Trefis | Is GitLab Stock Worth The Wait? | 2026-11-19 | opinion | https://www.trefis.com/stock/gtlb/articles/626874/is-gitlab-stock-worth-the-wait/2026-11-19 |
| 36 | Insider Monkey (via Yahoo) | Madison Small Cap Fund Q3 letter | 2026-10 | press | https://finance.yahoo.com/markets/stocks/articles/gitlab-inc-gtlb-eases-ai-135503599.html |
| 37 | Investing.com | GTLB consensus estimates | 2026-11 | press | https://www.investing.com/equities/gitlab-consensus-estimates |
| 38 | GitLab handbook repo; GitLab blog; Blind | Compensation calculator page; 2018 iteration; "went private" | 2018–2026 | primary / opinion | https://about.gitlab.com/blog/gitlabs-global-compensation-calculator-the-next-iteration |
| 39 | GitLab Handbook | Handbook homepage; Handbook Usage | read 2026-11-23 | primary | https://handbook.gitlab.com/handbook |
| 40 | GitLab Docs | Licensing and Compatibility | — | primary | https://docs.gitlab.com/development/licensing |
| 41 | Adaptavist; Schneider IT | GitLab Transcend 2026; GitLab Flex | 2026-06 | press | https://www.adaptavist.com/blog/gitlab-transcend-2026-key-announcements--what-they-mean |
| 42 | Manav Khurana, GitLab blog | Transcend India announcements | 2026-10-06 | primary | https://about.gitlab.com/blog/transcend-india-announcements |
| 43 | Motley Fool (via Yahoo); Investing.com | Co-founder trims position (Form 4) | 2026-04; 2026-11 | press | https://finance.yahoo.com/markets/stocks/articles/co-founder-trims-position-gitlab-020338467.html |
| 44 | GitLab blog | Pursuing faster time-to-merge for wider community contributions | undated | primary | https://about.gitlab.com/blog/pursuing-faster-time-to-merge-for-wider-community-contributions |
| 45 | Insider Monkey (via Yahoo) | GitLab seen as potential buyout candidate | 2026-02-06 | press | https://finance.yahoo.com/news/gitlab-gtlb-seen-potential-buyout-053232598.html |
| 46 | GitLab | What's new / direction | read 2026-11-23 | primary | https://about.gitlab.com/direction/ |
