# Toyota and the framework: comparison

| Field | Value |
|---|---|
| Study ID | CS-001 |
| Practice IDs | TOY-01 to TOY-19 |
| Framework version compared | GitHub README as read on 2026-10-12 (4 commits) |
| Written | 2026-10-12 |
| Last updated | 2026-11-23 |
| Sources | listed under *Sources* at the end of this file (source numbers in brackets) |

Area codes, fit values and how this file feeds decisions: see `../README.md`.

## 1. Summary

Toyota **confirms** two things the framework already says: the customer defines what is valuable, and the company keeps improving. It **adds** five things the framework doesn't cover yet: a way to surface problems at once, one accountable owner per product, respect for employees and suppliers, a long-term horizon with a limit on growth, and concrete daily mechanisms that carry the ideas. It **differs** from the framework in three places: Toyota keeps product development internal, shows little to the public, and sets prices from the market rather than from disclosed costs.

The places where Toyota differs are where the framework is making its own bet. Toyota's two biggest failures (the 2009–2010 recalls and the 2022–2024 testing scandals) happened where it wasn't transparent to the outside, which is some evidence for the framework's bet, not against it.

## 2. Overview

| ID | Toyota practice | Area | Fit | Decision topic |
|---|---|---|---|---|
| TOY-01 | The customer defines value; build what is ordered (pull) | PD | match | — |
| TOY-02 | Stop the line: anyone can halt work when something is wrong (jidoka, andon) | TR, CI | gap | FD-03, FD-06 |
| TOY-03 | Kaizen: the people doing the work improve it, against written standard work | CI | partial | FD-06 |
| TOY-04 | Go and see for yourself (genchi genbutsu) | PD | gap | FD-05 |
| TOY-05 | One chief engineer owns the product and the customer's voice | PD, PM | gap | FD-05 |
| TOY-06 | Product development stays inside the company | PD | differs | FD-05 |
| TOY-07 | Visual management, obeya room, one-page A3 reports | PM | partial | FD-06 |
| TOY-08 | Little transparency towards the public | TR | differs | FD-03 |
| TOY-09 | Target costing: market price first, cost made to fit | PR | differs | FD-04 |
| TOY-10 | Respect for people: developing people is the route to quality | PE | gap | FD-02 |
| TOY-11 | Long-term supplier partnerships | SU | gap | FD-02 |
| TOY-12 | Long-term philosophy over short-term financial results | LT | gap | FD-07 |
| TOY-13 | Growth limited by how fast people can be developed (lesson of 2010) | LT | gap | FD-07 |
| TOY-14 | Nemawashi: build agreement before a decision | PM | partial | FD-05 |
| TOY-15 | Hansei: honest reflection on mistakes | TR, CI | partial | FD-03 |
| TOY-16 | "Customer First" in sales and after-sales service | CO | partial | — |
| TOY-17 | Ownership that shields the long term (family influence, cross-shareholdings) | OW | gap | FD-01 |
| TOY-18 | Falsified certification across the group (Hino, Daihatsu, Toyota Industries, Toyota), traced to schedule pressure | TR, CI | differs | FD-03, FD-06, FD-07 |
| TOY-19 | Supplier terms enforced unilaterally by a group unit (2024 subcontract-law violation) | SU | differs | FD-02 |

Count: 1 match, 5 partial, 8 gap, 5 differs (TOY-18 and TOY-19 added 2026-11-23).

## 3. Practices in detail

### TOY-01: The customer defines value; build what is ordered

- **What Toyota does:** Anything the customer wouldn't pay for is waste. Production is pulled by actual orders (kanban, just-in-time) instead of pushed into stock. [study 3b]
- **Why it works for Toyota:** No overproduction, less inventory hiding problems, fast feedback when something goes wrong.
- **Fit:** match. The framework is built around customer needs.
- **Transfer:** For a software or product business: build what users actually use; measure use, not requests; drop roadmap items nobody needs.

### TOY-02: Stop the line

- **What Toyota does:** Any worker can pull the andon cord and stop production when something is wrong. Problems surface at once instead of being passed on. [study 3b]
- **Why it works:** Small problems get fixed before they become recalls; it signals that quality beats volume.
- **Fit:** gap. The framework says nothing about how problems surface internally or who can stop a release.
- **Transfer:** A rule that anyone (employee, and possibly a trusted community member) can raise a blocking issue that holds a release until it's looked at. In software: release gates and an incident process.

### TOY-03: Kaizen on standard work

- **What Toyota does:** Work is written down as a standard; the people doing it improve it in small steps. [study 3a, 3b]
- **Why it works:** Improvements stick because there's a baseline, and they come from the people who see the problems.
- **Fit:** partial. The framework's "continuous improvement" is driven by customer and community feedback; Toyota's by employees, against a written baseline.
- **Transfer:** Use both sources of improvement; keep documented processes as the baseline (fits the framework's documentation strategy).

### TOY-04: Go and see for yourself

- **What Toyota does:** Decisions rest on what you saw at the source. The 2004 Sienna chief engineer drove about 53,000 miles through every US state, every Canadian province and most of Mexico. [3]
- **Why it works:** Customers often can't say what they need; watching them finds what surveys and feedback forms miss.
- **Fit:** gap. The framework relies on feedback channels and forums, which capture what people say, not what they do.
- **Transfer:** Regular direct observation of users (sessions, support shadowing, site visits) alongside community input.

### TOY-05: One chief engineer owns the product

- **What Toyota does:** One person owns the whole product and speaks for the customer, leading through knowledge more than formal authority. [study 3b]
- **Why it works:** Clear accountability and a coherent product, with no design by committee.
- **Fit:** gap, with tension. The framework says nothing about who decides, and "community-driven" can be read as "the community decides".
- **Transfer:** Community input is open, but one named owner decides and publishes the reasons.

### TOY-06: Product development stays inside the company

- **What Toyota does:** Development is closed; customer insight comes in through observation and the chief engineer, not public participation.
- **Why it works for Toyota:** Protects competitive advantage and safety-critical engineering; fits a capital-heavy product with long cycles.
- **Fit:** differs. The framework opens product development to public scrutiny and input.
- **Candidate for explicit rejection:** keep development open, but borrow the decision discipline of TOY-04 and TOY-05.

### TOY-07: Visual management, obeya room, A3 reports

- **What Toyota does:** A project's status is on the walls of a "big room"; problems and proposals are written on one page (A3). [study 3b]
- **Why it works:** Everyone sees the same picture; the A3 format forces clear thinking.
- **Fit:** partial. Same idea as the framework's open project management, but for employees only.
- **Transfer:** Public boards plus a standard one-page format for proposals and decisions.

### TOY-08: Little transparency towards the public

- **What Toyota does:** Toyota is very open inside and much less so outside. In 2010 Akio Toyoda said growth had outpaced people development [1]. Testing scandals in the group followed in 2022–2024 (to verify in the study). Investors called the 2026 Toyota Industries buyout opaque until the price was raised [7].
- **Why it works for Toyota:** It works for internal problem-solving; it doesn't prevent failures where the company's own priorities are the problem.
- **Fit:** differs. The framework makes governance, development and pricing public.
- **Candidate for explicit rejection:** keep public transparency, and define its limits (personal data, supplier terms, security).

### TOY-09: Target costing

- **What Toyota does:** The price comes from what customers will pay; cost is reduced until the product fits with a fair profit for Toyota and its suppliers. Costs are not disclosed. [4]
- **Why it works:** Constant pressure to cut waste; prices stay competitive.
- **Fit:** differs. The framework discloses costs so the price can be justified (cost-plus logic).
- **Candidate to adapt:** combine a market reference price with published costs and a rule for where efficiency gains go (lower prices, reinvestment or profit).

### TOY-10: Respect for people

- **What Toyota does:** Developing people is the core of the system. "At Toyota, we believe the key to making quality products is to develop quality people." [1]
- **Why it works:** Skilled, trusted people find and fix problems; quality follows.
- **Fit:** gap. Employees appear only in the framework's stakeholder glossary.
- **Transfer:** A principle on how employees are developed, involved and treated.

### TOY-11: Long-term supplier partnerships

- **What Toyota does:** Suppliers are partners over decades. After the 1997 Aisin fire, suppliers improvised production and Toyota lost only about 5 days; Toyota and Aisin reimbursed the helpers and paid a bonus. [2]
- **Why it works:** Trust pays back in a crisis; suppliers share improvements.
- **Fit:** gap. Suppliers appear only in the glossary.
- **Transfer:** A principle on fair, long-term supplier relationships; could connect to transparent pricing (fair terms behind the published costs).

### TOY-12: Long-term philosophy over short-term results

- **What Toyota does:** Liker's first Toyota principle: base decisions on a long-term philosophy, even at the expense of short-term financial goals. [study 3a]
- **Why it works:** Allows long bets (hybrids, Prius 1997) and protects the system from quarterly pressure.
- **Fit:** gap.
- **Transfer:** State the time horizon explicitly in the framework.

### TOY-13: Growth limited by people development

- **What Toyota does:** Its own lesson from 2010: "We pursued growth over the speed at which we were able to develop our people and our organization." [1]
- **Why it matters:** Same pattern as Nike's oversupply and Starbucks' "manufacturing facility".
- **Fit:** gap.
- **Transfer:** A growth guardrail: don't scale faster than people and principles can follow.

### TOY-14: Nemawashi

- **What Toyota does:** Agreement is built with everyone affected before a decision is formally made.
- **Why it works:** Decisions are slow to make but fast to carry out.
- **Fit:** partial. The framework wants open discussion but has no decision process.
- **Transfer:** Define how open discussion turns into a decision: who decides, by when, how dissent is recorded.

### TOY-15: Hansei

- **What Toyota does:** Honest reflection on mistakes, even after a success.
- **Fit:** partial. The framework's transparency could make this public.
- **Transfer:** Public post-mortems after failures and missed commitments.

### TOY-16: "Customer First" in sales and after-sales

- **What Toyota does:** From the early sales network on, thorough after-sales service is seen as key to customers' trust. [8]
- **Fit:** partial. The framework covers communication but not support and service after the sale.
- **Transfer:** Possibly a later decision topic on customer support; note only for now.

### TOY-17: Ownership that shields the long term

- **What Toyota does:** Family influence (a small direct stake, under 2 %) through the group network and cross-shareholdings, which have been unwound since 2023; Toyota Industries was taken private in 2026 [N41, N47, N48]. The cost: minority shareholders called the Toyota Industries buyout undervalued and opaque until Toyota raised the price in 2026. [7]
- **Fit:** gap. The framework has no section on ownership and capital.
- **Candidate:** adapt the goal (protect the long term), reject the means (cross-shareholdings work against transparency).

### TOY-18: Falsified certification across the group

- **What Toyota does:**
  - **Hino:** falsified emissions data from at least 2003.
  - **Daihatsu:** rigged safety tests in 64 models, going back to 1989.
  - **Toyota Industries:** engine tests run with non-production software.
  - **Toyota itself:** 7 models tested against wrong standards (2024).
  - **Causes named by the investigations:** "management's promotion of short-term development" (Daihatsu) and no "psychological safety" to challenge superiors (Hino). Toyota admitted the added OEM work "may have significantly increased (Daihatsu's) burden".

  [N14, N15, N20, N22, N24, N28]
- **Fit:** differs. Stop-the-line (TOY-02) and hansei (TOY-15) didn't work where schedule pressure came from the parent and problems weren't visible to outsiders.
- **Lesson for FD-03, FD-06 and FD-07:** internal transparency isn't enough without outside visibility. Growth and schedule targets need a quality guardrail that subsidiaries and suppliers can invoke.

### TOY-19: Supplier terms enforced unilaterally

- **What Toyota does:** in 2024 the fair-trade regulator found that a Toyota unit made dozens of suppliers store dies without pay and take back goods without inspection; the money was repaid. Japan's amended Subcontract Act (2026) now bans unilateral price-setting [N63, N64].
- **Fit:** differs from the long-term supplier partnership Toyota is known for (TOY-11).

## 4. Where the framework goes further than Toyota

These are the framework's own bets. Toyota doesn't do them, so other companies have to supply the evidence for or against.

- Public transparency of governance, development and pricing: Buffer, GitLab, Everlane (CS-002, CS-003, CS-010)
- Community participation in product development: LEGO Ideas, Framework Computer (CS-005, CS-004)
- Cost disclosure as the basis for price: Everlane, Framework Computer, Costco's markup cap as an alternative (CS-010, CS-004, CS-006)
- Public roadmaps and task boards: Buffer, GitLab (CS-002, CS-003)

## 5. Candidates for explicit rejection

Practices that work for Toyota where the framework would deliberately choose otherwise. Final decisions are in `../decisions.md`.

- TOY-06 (closed product development): keep development open.
- TOY-08 (little public transparency): keep public transparency, with defined limits.
- TOY-17, the means only (cross-shareholdings): look for protections that don't need opacity.
- TOY-09, partly (prices without disclosed costs): keep cost disclosure, adapt the idea of a market reference price.

## 6. Open questions for the decisions

- Can a small company afford Toyota's people investment (TOY-10) while also being radically open?
- Does open product development need a single owner (TOY-05) more than closed development does, because there are more voices?
- Which parts of target costing (TOY-09) survive when costs are public?

## 7. Updates

- 2026-10-12: comparison written from the study's sections 3 and 4.
- 2026-11-23: TOY-17 detail confirmed (cross-shareholdings unwound; Toyota Industries taken private); TOY-18 and TOY-19 added from the group scandals.

## Sources

Source list from the underlying company study. Numbering matches the brackets above.

| # | Author / outlet | Title | Date | Type | Link |
|---|---|---|---|---|---|
| 1 | Toyota | Prepared testimony of Akio Toyoda before the US House Committee on Oversight and Government Reform | 2010-02-24 | primary | https://global.toyota/detail/2364044 |
| 2 | Wikipedia (citing Nishiguchi and Beaudet, *MIT Sloan Management Review*, Fall 1998, and *The Wall Street Journal*, 1997-05-08) | 1997 Aisin fire | accessed 2026-10-12 | reference | https://en.wikipedia.org/wiki/1997_Aisin_fire |
| 3 | Steve Portigal | Genchi genbutsu – that's Toyota for "user research" | | blog | https://portigal.com/genchi-genbutsu-thats-toyota-for-user-research/ |
| 4 | Lean Enterprise Institute | Lexicon: Target Cost | | reference | https://www.lean.org/lexicon-terms/target-cost/ |
| 5 | Gray | The Toyota Way 2001 house: lean for the 21st century | | industry article | https://www.gray.com/insights/the-toyota-way-2001-house-lean-for-the-21st-century |
| 6 | Books and papers (not yet read in this archive) | Womack, Jones, Roos 1990; Womack, Jones 1996; Spear, Bowen, HBR 1999; Liker 2004; Morgan, Liker 2006; Clark, Fujimoto 1991 | | books / research | |
| 7 | The Manila Times (Reuters) | Elliott agrees to Toyota's increased $30 billion tender offer for Toyota Industries | 2026-03-03 | wire | https://www.manilatimes.net/2026/03/03/business/foreign-business/elliott-agrees-to-toyotas-increased-30-billion-tender-offer-for-toyota-industries/2291097 |
| 8 | Toyota Commemorative Museum of Industry and Technology | Establishment of the Sales Network – "Customer First" Philosophy | | primary (company museum) | https://tcmit.org/vgt/car/english/scene-05-iframe/target-03 |

| # | Author / outlet | Title | Date | Type | Link |
|---|---|---|---|---|---|
| N1 | Toyota (75 Years) | The Birth of Jidoka | — | primary | https://www.toyota-global.com/company/history_of_toyota/75years/text/taking_on_the_automotive_business/chapter1/section1/item4.html |
| N2 | Toyota (75 Years) | Chronological table 1921–1930 | — | primary | https://www.toyota-global.com/company/history_of_toyota/75years/data/overall_chronological_table/1921.html |
| N3 | Toyota | Type G Automatic Loom donated to Science Museum | — | primary | https://global.toyota/en/detail/7953361 |
| N4 | Toyota (75 Years) | Establishment of Toyota Motor Co. and the Koromo Plant | — | primary | https://www.toyota-global.com/company/history_of_toyota/75years/text/taking_on_the_automotive_business/chapter2/section4/item3.html |
| N5 | Toyota (75 Years) | The Origins of Just-in-Time | — | primary | https://www.toyota-global.com/company/history_of_toyota/75years/text/taking_on_the_automotive_business/chapter2/section4/item5.html |
| N6 | Toyota (75 Years) | Toyota Production System | — | primary | https://www.toyota-global.com/company/history_of_toyota/75years/data/automotive_business/production/system/change.html |
| N7 | Toyota (75 Years) | Development and Deployment of the TPS | — | primary | https://www.toyota-global.com/company/history_of_toyota/75years/text/entering_the_automotive_business/chapter1/section4/item4.html |
| N8 | Toyota (75 Years) | Joint Venture with GM | — | primary | https://www.toyota-global.com/company/history_of_toyota/75years/text/leaping_forward_as_a_global_corporation/chapter1/section3/item2.html |
| N9 | Toyota (75 Years) | Developing the Lexus | — | primary | https://www.toyota-global.com/company/history_of_toyota/75years/text/leaping_forward_as_a_global_corporation/chapter2/section3/item5_a.html |
| N10 | Toyota (75 Years); Toyota | Prius and hybrid strategy; Story behind the Prius | — | primary | https://www.toyota-global.com/company/history_of_toyota/75years/text/leaping_forward_as_a_global_corporation/chapter4/section8/item1.html |
| N11 | Toyota (75 Years) | Expansion of Recalls | — | primary | https://www.toyota-global.com/company/history_of_toyota/75years/text/leaping_forward_as_a_global_corporation/chapter5/section3/item1.html |
| N12 | US DOJ (SDNY) | Toyota Deferred Prosecution Agreement | 2014-03-19 | primary | https://www.justice.gov/sites/default/files/opa/legacy/2014/03/19/toyota-def-pros-agr.pdf |
| N14 | Hino Motors | Special Investigation Committee results | 2022-08-02 | primary | https://www.hino-global.com/corp/for_investors/disclosure/assets/e9e9de2a2a41bb0b5079f138f042b1a3.pdf |
| N15 | Reuters (via Yahoo) | Hino falsified emissions data from at least 2003 | 2022-08-02 | wire | https://finance.yahoo.com/news/committee-probing-toyota-unit-hino-002300389.html |
| N17 | US DOJ | Court sentences Hino Motors; over $1.6B in penalties | 2025-03-19 | primary | https://www.justice.gov/opa/pr/court-sentences-hino-motors-ltd-toyota-subsidiary-and-imposes-over-16b-penalties-emissions |
| N18 | Reuters (via Yahoo) | Hino reaches $1.6 billion settlement | 2025-01-15 | wire | https://finance.yahoo.com/news/toyota-unit-hino-motors-charged-171352013.html |
| N20 | Daihatsu | Results of the Independent Third-Party Committee | 2023-12-20 | primary | https://www.daihatsu.com/news/2023/20231220-4.html |
| N21 | Toyota | Additional procedural irregularities by Daihatsu | 2023-12-20 | primary | https://global.toyota/en/newsroom/corporate/40238738.html |
| N22 | Global Fleet; CNBC/Reuters | Daihatsu stops all shipments | 2023-12 | press | https://www.cnbc.com/2023/12/20/toyotas-daihatsu-to-halt-vehicle-shipments-as-safety-scandal-widens.html |
| N24 | Toyota | Certification irregularities at Toyota Industries | 2024-01-29 | primary | https://global.toyota/en/newsroom/corporate/40376368.html |
| N25 | Toyota Industries | Investigation on engine certification | 2024-01-29 | primary | https://www.toyota-industries.com/news/item/20240129_release_e.pdf |
| N26 | Toyota Times | Toyota Group Vision | 2024-01-30 | primary | https://toyotatimes.jp/en/toyota_news/toyota_group_vision/001_1.html |
| N28 | Toyota | Results of investigation on model certification | 2024-06-03 | primary | https://global.toyota/en/newsroom/corporate/40920588.html |
| N31 | Toyota | Correction order | 2024-07-31 | primary | https://global.toyota/en/newsroom/corporate/41314045.html |
| N32 | AP (via Courthouse News); Car and Driver | Toyota apologizes for cheating on vehicle testing | 2024-06-03 | press | https://www.courthousenews.com/toyota-apologizes-for-cheating-on-vehicle-testing-and-halts-production-of-three-models |
| N34 | Toyota | Voting results, 119th AGM | 2023-06-15 | primary | https://global.toyota/pages/global_toyota/ir/stock/2023_voting_results_en.pdf |
| N35 | Toyota | Voting results, 120th AGM | 2024-06-19 | primary | https://global.toyota/pages/global_toyota/ir/stock/2024_voting_results_en.pdf |
| N36 | Toyota (via LSE RNS) | Voting results, 122nd AGM | 2026-06-18 | primary | http://www.rns-pdf.londonstockexchange.com/rns/8202I_1-2026-6-18.pdf |
| N38 | Toyota | Transition to a Company with an Audit and Supervisory Committee | 2025-02-25 | primary | https://global.toyota/en/newsroom/corporate/42267575.html |
| N39 | Toyota | Executive changes and board structure | 2026-02 | primary | https://global.toyota/en/newsroom/corporate/44070196.html |
| N40 | Toyota | Form 20-F FY2026 (read in parts) | 2026-06 | primary | https://global.toyota/pages/global_toyota/ir/library/sec/20-F_202603_final.pdf |
| N41 | Business Times (Bloomberg) | Toyota founding family biggest winner in unit takeover | 2026 | press | https://www.businesstimes.com.sg/international/global/toyota-founding-family-biggest-winner-unit-takeover-battle |
| N44 | Elliott (PR Newswire) | Elliott opposes revised tender offer | 2026-01-15 | primary (party) | https://www.prnewswire.com/apac/news-releases/elliott-opposes-toyota-fudosans-revised-tender-offer-for-toyota-industries-corporation-302664093.html |
| N46 | BigGo Finance (weak) | Toyota raises offer to ¥20,600 | 2026-03 | press | https://finance.biggo.com/news/k5ohrpwBvthpMgHB931u |
| N47 | Toyota Industries | Results of tender offer | 2026-03-24 | primary | https://www.toyota-industries.com/news/item/20260324_docment_e02.pdf |
| N48 | Reuters (via Yahoo) | Toyota group to sell 8 % Denso stake | 2023-11 | wire | https://finance.yahoo.com/news/denso-toyota-group-sell-denso-072146172.html |
| N50 | Toyota Industries | Sale of cross-shareholdings | 2024-10-31 | primary | https://www.toyota-industries.com/news/2024/10/31/008727/index.html |
| N51 | Toyota | Changes to executive structure | 2026-02-06 | primary | https://global.toyota/en/newsroom/corporate/43951723.html |
| N52 | CNBC | Toyota promotes CFO Kenta Kon as CEO | 2026-02-06 | press | https://www.cnbc.com/2026/02/06/toyota-ceo-koji-sato-to-step-down-and-be-replaced-by-cfo-kenta-kon-profit-forecast.html |
| N53 | Reuters (via Arab News Japan) | Shareholders back Toyoda and new CEO Kon | 2026-06-17 | wire | https://www.arabnews.jp/en/business/toyota-shareholders-back-toyoda-as-chairman-and-new-ceo-kon-at-annual-meeting-172323 |
| N54 | Toyota | FY2026 financial results | 2026-05-08 | primary | https://pressroom.toyota.com/tmc-announces-april-through-march-2026-financial-results/ |
| N55 | IBTimes JP | Toyota forecasts lower profit after tariff-hit fiscal 2026 | 2026-05 | press | https://jp.ibtimes.com/toyota-forecasts-lower-profit-after-tariff-hit-fiscal-2026-100850 |
| N56 | Toyota | April–September 2026 results | 2026-11-05 | primary | https://pressroom.toyota.com/tmc-announces-april-through-september-2026-financial-results |
| N57 | Toyota | FY2027 Q2 presentation | 2026-11-05 | primary | https://global.toyota/pages/global_toyota/ir/financial-results/2027_2q_presentation_en.pdf |
| N58 | Toyota | Investor relations calendar | 2026-11 | primary | https://global.toyota/en/ir |
| N59 | Toyota | Organizational changes effective 2027-01-01 | 2026-11-05 | primary | https://global.toyota/en/newsroom/corporate/44970123.html |
| N60 | Toyota Times | Business structure reforms | 2026-11-13 | primary | https://toyotatimes.jp/en/toyota_news/financial_results_2027/003.html |
| N61 | Asahi Shimbun | Major firms meet wage demands | 2026-03 | press | https://www.asahi.com/ajw/articles/16433618 |
| N63 | Japan Times | Toyota unit violated subcontractor protection law | 2024-07-05 | press | https://www.japantimes.co.jp/business/2024/07/05/companies/toyota-subcontract-payment |
| N64 | ISMEC | Japan's revised Subcontract Act 2026 | 2026 | industry explainer | https://en.ismec.jp/insights/japan-subcontract-act-toritekiho-2026 |
| N65 | Reuters (via Yahoo) | Toyota suppliers feeling profit pressure from Iran war | 2026-04-28 | wire | https://ca.finance.yahoo.com/news/toyota-suppliers-feeling-profit-pressure-103210424.html |
| N66 | Kelley Blue Book | Consumer Reports reliability | 2025-12 | press | https://www.kbb.com/car-news/consumer-reports-toyota-subaru-make-the-most-reliable-cars |
| N67 | Consumer Reports | Who makes the most reliable new cars? | 2026-06 | rating | https://www.consumerreports.org/cars/car-reliability-owner-satisfaction/who-makes-the-most-reliable-cars-a7824554938 |
| N68 | CarPro (J.D. Power) | 2026 Vehicle Dependability Study | 2026-02-18 | press | https://www.carpro.com/blog/j.d.-power-2026-vehicle-dependability-study-results |
