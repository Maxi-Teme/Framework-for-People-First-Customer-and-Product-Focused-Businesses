# Framework decisions

The decision log for the framework. Each **decision topic** (`FD-xx`, never reused) is a question the framework has to answer. Company comparisons feed it with practices (`TOY-01`, …); a topic is decided once enough companies have been compared.

**The question behind all topics (restated 2026-11-23):** *what makes a good company with a real customer and product focus, and what keeps it that way?* The draft framework's four principles are hypotheses, not fixed values. FD-09 to FD-13 test them directly; every other topic is judged against the question, not against the draft. A practice that differs from the draft can be the better answer.

**Rules**
- Only the maintainer decides. Research sessions may add practices, evidence, options and recommendations, and may open new topics with status `open`, but never fill in a decision.
- Every decision states its outcome for each practice considered, so it's clear where the framework **explicitly decides against** something that works for another company, and why.
- A decision isn't finished until the framework change is written down; "Applied in repo" tracks whether it's in the GitHub README yet.
- **What, not how** (2026-11-23): the framework README states what a company commits to. Methods, examples and evidence stay here in the decision log unless the method itself is key. Example: "publish a price rule and prove it is kept" goes in the framework; margin caps, price logs and audits as ways to do it stay here (FD-04).

**Outcomes (per practice):** `adopt` (take it as is) · `adapt` (take the idea, change the method) · `reject` (decide against it, even though it works elsewhere; say why and what we do instead) · `park` (not now)

**Status (per topic):** `open` · `decided YYYY-MM-DD` · `superseded by FD-xx`

FS-01 to FS-07 in earlier notes are the same topics as FD-01 to FD-07 (renamed 2026-10-12).

## Overview

| ID | Question | Areas | Practices considered | Status |
|---|---|---|---|---|
| FD-01 | How does the framework protect its principles against owner and investor pressure? | OW | TOY-17, BUF-09, BUF-10, BUF-11, EVL-08, EVL-09, PAT-01, PAT-02, PAT-13, FRM-14, GIT-03, GIT-14, LEG-07, LEG-08, COS-15, SBX-12, SBX-13, BOE-03, BOE-14, BOE-15, SWA-02, SWA-06, SWA-11, NKE-11, NKE-13, HAI-03, HAI-11, BNJ-01, BNJ-08, BNJ-09, BNJ-10, BNJ-11, BNJ-14, FAI-12 | decided 2026-11-23 |
| FD-02 | Do employees and suppliers get their own principle? | PE, SU | TOY-10, TOY-11, BUF-02, BUF-03, BUF-07, BUF-14, EVL-03, EVL-07, PAT-08, PAT-09, PAT-10, GIT-11, GIT-12, GIT-13, GIT-15, LEG-12, COS-09, COS-10, COS-11, SBX-07, SBX-08, SBX-09, SBX-10, SBX-12, BOE-07, BOE-08, BOE-09, BOE-10, BOE-11, SWA-03, SWA-04, SWA-05, SWA-10, NKE-05, NKE-12, TOY-19, HAI-01, HAI-02, HAI-03, HAI-08, HAI-10, BNJ-02, BNJ-03, BNJ-05, BNJ-07, FAI-05, FAI-14 | decided 2026-11-23 |
| FD-03 | What is transparent inside the company, what is public, and what stays private? | TR | TOY-02, TOY-08, TOY-15, BUF-01, BUF-02, BUF-04, BUF-05, BUF-09, BUF-13, EVL-02, EVL-03, EVL-12, PAT-02, PAT-06, PAT-07, FRM-08, FRM-11, FRM-12, FRM-17, GIT-01, GIT-02, GIT-03, GIT-04, GIT-11, GIT-12, GIT-15, LEG-06, LEG-13, COS-07, COS-08, SBX-02, BOE-04, BOE-05, BOE-15, NKE-02, NKE-03, NKE-12, TOY-18, HAI-04, BNJ-06, FAI-02, FAI-03, FAI-13 | open |
| FD-04 | How is a fair price set and explained? | PR | TOY-09, BUF-06, BUF-07, BUF-15, BUF-16, EVL-01, EVL-04, EVL-11, PAT-05, PAT-07, FRM-01, FRM-02, FRM-03, FRM-04, FRM-05, FRM-06, GIT-06, GIT-08, GIT-09, LEG-09, LEG-10, COS-01, COS-02, COS-03, COS-04, COS-05, COS-06, COS-08, COS-14, SBX-04, SBX-05, SBX-15, SWA-01, SWA-02, SWA-12, NKE-07, NKE-10, HAI-14, BNJ-13, FAI-01 | open |
| FD-05 | Who decides about the product, and how does community input become a decision? | PD, PM | TOY-04, TOY-05, TOY-06, TOY-14, BUF-08, BUF-17, PAT-04, FRM-08, FRM-09, FRM-10, GIT-05, GIT-06, GIT-07, GIT-10, LEG-01, LEG-02, LEG-04, LEG-05, COS-04, COS-13, SBX-01, BOE-01, BOE-13, SWA-07, NKE-01, NKE-08, NKE-09, HAI-01, HAI-05, HAI-06, HAI-08, HAI-12, HAI-13, BNJ-12, FAI-10, FAI-11 | open |
| FD-06 | Which concrete mechanisms and measures carry each principle? | CI, PM, TR | TOY-02, TOY-03, TOY-07, BUF-04, BUF-05, BUF-15, EVL-06, PAT-06, FRM-02, FRM-03, FRM-13, GIT-01, GIT-03, GIT-07, LEG-06, LEG-13, COS-07, SBX-03, BOE-06, BOE-07, BOE-08, BOE-12, SWA-08, SWA-09, NKE-14, TOY-18, HAI-07, HAI-09, BNJ-06, FAI-07 | open |
| FD-07 | Does the framework set a long-term horizon and a limit on growth? | LT | TOY-12, TOY-13, BUF-11, BUF-12, EVL-10, PAT-12, FRM-07, FRM-15, GIT-14, LEG-03, LEG-07, LEG-14, COS-15, SBX-06, SBX-14, BOE-02, BOE-03, BOE-10, SWA-03, SWA-05, SWA-11, NKE-06, NKE-13, TOY-18, BNJ-04, FAI-08, FAI-09 | decided 2026-11-23 |
| FD-08 | Does the framework cover environmental and supply-chain impact, and how is it verified? | EN, SU | EVL-03, EVL-05, EVL-06, PAT-03, PAT-04, PAT-05, PAT-06, PAT-10, FRM-07, FRM-16, LEG-10, LEG-11, LEG-12, COS-12, SBX-11, NKE-02, NKE-03, NKE-04, NKE-05, NKE-14, BNJ-02, BNJ-07, FAI-03, FAI-04, FAI-05, FAI-06, FAI-07, FAI-09 | open |
| FD-09 | What is the framework's core goal, and does its name and scope fit it? | all | (cross-cutting; see topic) | decided 2026-11-23 |
| FD-10 | Is transparency a goal or a means, and how much of it serves customers and product? | TR | TOY-02, TOY-08, TOY-15, BUF-01, PAT-07, FRM-11, FRM-17, GIT-03, COS-08, NKE-02, BOE-04, BNJ-06, FAI-02, FAI-03 | decided 2026-11-23 |
| FD-11 | Is cost disclosure needed for fair prices, or is a published price rule enough? | PR | BUF-06, EVL-01, FAI-01, FRM-01, FRM-02, FRM-03, COS-01, COS-02, COS-05, COS-08, SWA-01, PAT-07, GIT-09, LEG-09, SBX-05, NKE-10, BNJ-13, HAI-14, FRM-17 | decided 2026-11-23 |
| FD-12 | Is community-driven development required, or one of several ways to stay close to customers? | PD | TOY-04, TOY-06, BUF-08, FRM-09, GIT-05, LEG-01, BOE-01, NKE-01, HAI-05, HAI-06, SBX-01 | decided 2026-11-23 |
| FD-13 | Are public roadmaps and task boards needed? | PM | BUF-08, GIT-05, FRM-10 | decided 2026-11-23 |

Meeting the guideline (practices from at least 3 companies, including a cautionary case) as of 2026-10-12: FD-01, FD-02, FD-03, FD-04, FD-06, FD-07. Not yet: FD-05 (Toyota, Buffer, Patagonia; no cautionary case yet), FD-08 (Everlane, Patagonia; needs a third company, e.g. Fairphone). Update 2026-11-23 after Framework Computer (CS-004): FD-08 now has three companies (Everlane, Patagonia, Framework) and meets the guideline; FD-05 has four companies but still no cautionary case.

Update 2026-11-23 after GitLab (CS-003): FD-05 now has a cautionary case (GitLab) and meets the guideline; FD-03 and FD-06 get their strongest cautionary evidence.

Update 2026-11-23 after Ben & Jerry's (CS-014): FD-01 now has its clearest contrast pair — Patagonia (purpose owns the company) vs Ben & Jerry's (purpose protected only by a contract with the owner, which failed).

Update 2026-11-23 after Fairphone (CS-015): FD-08 now has five companies with practices (Everlane, Patagonia, Framework Computer, Nike, Fairphone), including a cautionary case, and is ready to decide.

Update 2026-11-23: FD-02 decided (principle 6 "People": living wage, public pay gap, recognised representation, no involuntary layoffs, fair long-term supplier terms). All principle-level topics are now decided; FD-03 to FD-06 and FD-08 settle details. FD-07 decided (long view; growth limited by quality and people; product and people funded before payouts; durable products where the product allows). FD-01 decided (principles anchored in ownership or legal form, with an independent enforcer; no capital whose terms override them). FD-13 decided (principle 4 dropped; covered by FD-12). All four draft principles are now decided (FD-10 to FD-13). FD-12 decided (closeness to users required, method free; defined path from input to decision with public reasons). FD-11 decided (published price rule plus proof by own figures or independent audit; guarantees left to FD-04). FD-10 decided (transparency is a means; first-order minimum set public, second-order proven another way). FD-09 decided (widen the goal to customer and product focus; rename later). Earlier the same day (reframing): FD-09 to FD-13 added to test the draft's own principles. Suggested order for deciding: FD-09 first (it sets the yardstick), then FD-10 and FD-11 (they change which practices count as rejections), then the rest.

## Explicit rejections

Practices that work for another company where the framework deliberately chooses otherwise. Filled in only when a topic is decided.

| Practice | Company | Why it works for them | Why we reject it | What we do instead | Decided in |
|---|---|---|---|---|---|
| BOE-04 | Boeing | — (it didn't work: it led to two fatal crashes and a criminal case) | Hiding safety-relevant information from users and regulators | Safety-relevant information is always public (FD-10 minimum set) | FD-10, 2026-11-23 |
| GIT-03 | GitLab | Let a new CEO reorient the company quickly | Principles held only as internal values were retired in one memo, without a public record | Commitments and their results are public; changes to them are made in public | FD-10, 2026-11-23 |
| EVL-08 | Everlane | Funded fast growth and a national brand | Capital whose terms required growth and an exit; ended in a sale to Shein | Only capital that accepts the anchored principles | FD-01, 2026-11-23 |
| EVL-09 | Everlane | A strong founder story built trust quickly | Values carried only by the founder and the brand; gone once he stepped back | Principles anchored in ownership or the legal form | FD-01, 2026-11-23 |
| BNJ-08 | Ben & Jerry's | Let the founders sell while keeping a mission board | A contract with the buyer as the only protection; largely unenforceable | Anchoring in ownership or the legal form, with an independent enforcer | FD-01, 2026-11-23 |
| BNJ-10 | Ben & Jerry's | Gives the parent full control of its subsidiary | The owner remade the guardian board and replaced the CEO | Guardians the owners cannot remove or redefine | FD-01, 2026-11-23 |
| BNJ-11 | Ben & Jerry's | Lets the parent control spending | The enforcer depended on the owner's money; funding was withheld | The enforcer has its own means | FD-01, 2026-11-23 |
| SWA-06 | Southwest Airlines | Raised the share price; the activist exited at a profit | Principles unprotected from board control; an 11 % holder reset the strategy | Principles a board majority cannot drop | FD-01, 2026-11-23 |
| GIT-14 | GitLab | Venture money and an IPO funded rapid growth | Values changed under growth and investor pressure | Only capital that accepts the anchored principles | FD-01, 2026-11-23 |
| SWA-02 | Southwest Airlines | Added fee revenue quickly | A public price promise reversed with an unpublished analysis | Commitments change only in public, with the reason (principles 1 and 3) | FD-01, 2026-11-23 |
| BOE-15 | Boeing | Closed a criminal case without a trial | Accountability through a checker the company chose itself | Checks by someone the company doesn't choose alone | FD-01, 2026-11-23 |
| EVL-10 | Everlane | Fast growth built the brand | Growth outran a slow supply chain; quality was cut | Growth limited by the ability to keep quality | FD-07, 2026-11-23 |
| SBX-14 | Starbucks | Store count and throughput raised revenue | Growth eroded the product experience, twice | Growth limited by the ability to keep quality | FD-07, 2026-11-23 |
| BOE-02 | Boeing | Higher margins and share price for years | Financial targets replaced the engineering and product principle | Long view over short-term financial goals; product funded first | FD-07, 2026-11-23 |
| BOE-03 | Boeing | Raised earnings per share | $43.5B of buybacks while R&D and workforce shrank relative to sales | Product and people funded before payouts; split public | FD-07, 2026-11-23 |
| BOE-10 | Boeing | Lowered capital needs on the 787 | Development risk pushed onto suppliers; outsourcing failed | Growth and schedules limited by what the company and its suppliers can do well | FD-07, 2026-11-23 |
| NKE-13 | Nike | Supported the share price | $12.1B of buybacks during the product decline | Product and people funded before payouts | FD-07, 2026-11-23 |
| SWA-11 | Southwest Airlines | Rewarded shareholders after the activist campaign | $2.9B to shareholders against $97M profit sharing, while promises to customers were dropped | Product and people funded before payouts; split public | FD-07, 2026-11-23 |
| TOY-18 | Toyota | Kept schedules and volume | Schedule pressure led to falsified certification across the group | Growth and schedule limits that reach subsidiaries and suppliers | FD-07, 2026-11-23 |
| EVL-07 | Everlane | Kept costs down and avoided a union | Layoffs 4 days after a request for union recognition; "transparency" used against the union | The company recognises any representation employees choose | FD-02, 2026-11-23 |
| SBX-09 | Starbucks | Delayed higher labour costs | No first contract five years after the first union vote | Representation recognised and negotiated with in good faith | FD-02, 2026-11-23 |
| SBX-07 | Starbucks | Made friendliness visible and uniform | Warmth enforced by discipline | People developed and heard, not policed into a feeling | FD-02, 2026-11-23 |
| NKE-05 | Nike | Kept supplier costs and liability down | Remedies for unpaid supplier wages disputed or delayed | Fair supplier terms; supply-chain wages a public goal with reported progress | FD-02, 2026-11-23 |
| TOY-19 | Toyota | Protected a group unit's margins | Supplier terms enforced unilaterally, breaking subcontracting law | Fair, long-term supplier terms | FD-02, 2026-11-23 |
| HAI-10 | Haier | Drove high individual performance | A pressure culture without protections | A living-wage floor and voice; results pay only above the floor | FD-02, 2026-11-23 |
| GIT-15 | GitLab | Cut costs quickly | Layoffs called "transparent" while plans stayed hidden | No involuntary layoffs | FD-02, 2026-11-23 |

Candidates so far (not decided), revised 2026-11-23. Only practices that harmed customers, the product, workers or trust are listed as rejection candidates; practices that merely differ from the draft moved to "re-check" below.

- **Harm-based candidates:** BOE-04 concealment of safety-relevant information; BOE-02/BOE-03 financial returns as the governing principle; BOE-13 shutting out expert users; SWA-02 reversing a public price promise without published evidence; SWA-06/SWA-11 principles left unprotected from board control; GIT-03 principles held only as internal values a CEO can retire alone; BNJ-08 a contract with the buyer as the only protection; BNJ-10/BNJ-11 guardians redefined or defunded by the owner; EVL-02 transparency chosen for what sells; EVL-07 treating employee organisation as a threat; EVL-08 high-valuation equity with growth expectations; EVL-09 values carried only by the founder and the brand story; EVL-10 growth that forces quality cuts; SBX-07 culture enforced by discipline; SBX-09 treating a union as an adversary; SBX-14 growth by store count without a quality limit; NKE-07 engineered scarcity; NKE-08 co-creation that can be withdrawn at will; HAI-10 pay and removal mechanisms without worker protections; HAI-13 suppressing community integrations; BUF-02 publishing every salary by name; BUF-11 founder control as the only protection; TOY-17 cross-shareholdings as a shield; TOY-18 falsified certification under schedule pressure.
- **To adapt, not reject:** COS-01 the markup cap (publish it); COS-06 windfall pass-through (make it a published rule); FRM-04 unilateral downgrades (let customers choose); LEG-01 the review gate (publish reasons); PAT-02 opaque trust governance (publish the structure's rules and flows).
- **Re-check (marked `recheck?` in `practices.md`; depends on FD-10 to FD-13):** PAT-07, FRM-17, GIT-09, COS-08, LEG-09, SBX-05, NKE-10, BNJ-13, HAI-14 (no cost or financial disclosure); TOY-08 (little public transparency); TOY-06 (closed product development); FRM-10 (no public roadmap); TOY-09 (prices without disclosed costs). Several of the most customer-focused companies studied (Costco, Toyota, LEGO) do these things.

## Topics

### FD-01: Ownership and capital

- **Question:** How does the framework protect its principles when owners or investors want something else?
- **Business-history evidence (Toyota group, added 2026-11-24):** a founding family keeps influence over a group with under 2 % of the shares, through cross-shareholdings among group companies and, since 2026, an unlisted group real-estate company (Toyota Fudosan, held by group companies, with the family head investing personally) that took a key group company private; the group is now unwinding part of the cross-shareholdings while "maintaining the capital ties that have sustained a strong relationship". Sources: Toyota, 2024-06-27 (https://global.toyota/en/newsroom/corporate/41080974.html); Just Auto via Yahoo Finance, 2025-06-03 (https://finance.yahoo.com/news/toyota-key-supplier-private-105344193.html); Bloomberg, 2026-03-03 (https://www.bloomberg.com/news/articles/2026-03-03/toyota-founding-family-is-biggest-winner-in-unit-takeover-battle). Analysis (medium confidence): influence without ownership can protect a long-term horizon, but it is anchoring by structure that outsiders can't see clearly; principle 5 asks for ownership and governance to be public, including such ties.
- **Business-history evidence (activist investors, added 2026-11-24):**
  - Board control without a majority: at Southwest an activist with 11–16 % of the economic interest won five board seats and the chair's early exit by settlement; the price promises went within months, and three of its directors stayed after its standstill ended. Sources: Dallas Morning News, 2024-10-24 (https://sportsday.dallasnews.com/business/airlines/2024/10/24/southwest-airlines-reaches-settlement-with-elliott-adds-new-board-directors); Dallas Morning News, 2025-02-07 (https://sportsday.dallasnews.com/business/airlines/2025/02/07/two-more-southwest-airlines-board-members-step-down-completing-elliott-makeover).
  - The other side: at Toyota Industries the same activist acted for minority shareholders against an undervalued take-private by the controlling group; the price rose twice, by 26 % in total. Sources: Jiji Press via Nippon.com, 2026-03-24 (https://www.nippon.com/en/news/yjj2026032400821); Bloomberg Law, 2026-03 (https://news.bloomberglaw.com/esg/elliott-set-for-500-million-gain-from-toyota-industries-fight). Analysis: anchoring that protects the principles must not become a shield for controlling owners against other owners; principle 5 (ownership and governance public) and fair treatment of all owners matter here.
- **Business-history evidence (Boeing, added 2026-11-23):** control can change through a merger even when the company is the buyer. Boeing was the surviving company in the 1997 McDonnell Douglas merger, but McDonnell Douglas's CEO became Boeing's No. 2 and later CEO, its former directors took a third of the board, and he later said he changed Boeing so "it's run like a business rather than a great engineering firm". Sources: New York Times, 1996-12-16 (https://www.nytimes.com/library/financial/1216boeing-mcdonnell.html); Chicago Tribune, 2004-02-29 (see `comparisons/boeing.md`). Bears on principle 6: anchoring has to hold against a merger partner's management, not only against outside investors.
- **Practices considered:** TOY-17 (family influence and cross-shareholdings shield the long term; cost: opacity towards minority shareholders); BUF-09, BUF-10, BUF-11 (Buffer); EVL-08, EVL-09 (Everlane); PAT-01, PAT-02, PAT-13 (Patagonia); FRM-14 (Framework Computer); GIT-03, GIT-14 (GitLab); LEG-07, LEG-08 (LEGO); COS-15 (Costco); SBX-12, SBX-13 (Starbucks); BOE-03, BOE-14, BOE-15 (Boeing); SWA-02, SWA-06, SWA-11 (Southwest Airlines); NKE-11, NKE-13 (Nike); HAI-03, HAI-11 (Haier); BNJ-01, BNJ-08, BNJ-09, BNJ-10, BNJ-11, BNJ-14 (Ben & Jerry's); FAI-12 (Fairphone).
- **From the Buffer comparison (CS-002):** in 2018 Buffer spent $3.3M, half its cash, to buy back shares from 7 of 16 Series A investors whose terms (a 9 % annual return protection, a liquidity veto) pointed to a venture path (BUF-10). It also published its fundraising terms and equity formula (BUF-09). But its values are protected mainly by the founder's 57 % stake; employees own 1.16 % of issued shares and investors still hold about 38 % with no exit plan (BUF-11). Lesson: a buyout works, but the lock-in should be structural, not personal.
- **From the Everlane comparison (CS-010):** the counter-case to Buffer. Venture capital from 2011, about $250M valuation in 2016, an $85M round led by private equity in 2020, $90M of debt in 2022, a private equity majority, then a sale to Shein for a reported $100M with nothing reported for common shareholders (EVL-08). No charter or owner commitment protected the values; the founder stepped back and learned of the sale from the press (EVL-09). His new brand: "no venture capital, no private equity".
- **From the Patagonia comparison (CS-012):** the structural answer Buffer and Everlane lacked. Since 2022 voting stock (about 2 %) sits in a purpose trust and non-voting stock (about 98 %) in a nonprofit that receives profits not reinvested: $180M by November 2025 (PAT-01). Benefit-corporation status since 2012 writes the purpose into the legal form (PAT-13). Costs: the family keeps control through the trust, the nonprofit can fund politics, and part of its spending isn't visible (PAT-02).
- **From the Framework Computer comparison (CS-004):** about $45M of venture money since 2021, led by Spark Capital, with the stated aim to "raise as little as possible"; in 2024 a $1M community round (100 accredited investors at $10,000 each) (FRM-14). Pre-orders and direct sales finance production (FRM-15). No financial disclosure, and in July 2026 a warning that absorbing costs would put the company "at real financial risk". Adds an option: reserve part of any outside round for the community, through a structure open to non-accredited investors.
- **From the GitLab comparison (CS-003):** a venture-backed, then listed company where the founder stepped back (2024) and a new CEO retired the values, including Transparency, in one memo (2026-05-11); the Values page was deleted five months later (GIT-03, GIT-14). No ownership structure or outside commitment protected them. What survived were promises made to outsiders (GIT-07). Adds an option: make the principles enforceable by the community (published promises, a foundation holding the trademark, or a golden share), not only by the board.
- **From the LEGO comparison (CS-005):** family holding (75 %) and foundation (25 %, receiving 25 % of dividends: DKK 2,250m in 2025), no outside investors, a planned generational handover (LEG-07). A trademark royalty (DKK 2,965m in 2025) flows to the family holding outside the foundation split, so the foundation's effective share is probably below 25 % (LEG-08). Shows a foundation share as a fixed, published purpose stake, and the need to report it against all cash flowing to owners.
- **From the Costco comparison (CS-006):** widely held, listed, no protective ownership; long-term orientation held by culture and results against analyst pressure (2004: "overly generous"), alongside six special dividends, the latest $30 a share (about $13.3B) in 2026 (COS-15).
- **From the Starbucks comparison (CS-007):** activist investors (Elliott, Starboard) drove a CEO change in 2024 (SBX-13); a board committee on labour, created after a majority shareholder vote in 2023, was dissolved in 2025, and shareholders filed to restore it for 2027 (SBX-12).
- **From the Boeing comparison (CS-008):** $43.5B of buybacks 2013–2019 while R&D and workforce shrank as a share of sales (BOE-03); since 2020 buybacks and dividends suspended and a $24B equity raise used for the balance sheet (BOE-14); a criminal case closed by a non-prosecution agreement with a company-chosen consultant, which the judge said "fails to secure the necessary accountability" (BOE-15). Shows where profits go, and who checks the company, are principle questions.
- **From the Southwest Airlines comparison (CS-009):** the clearest case: an activist with about 11 % economic interest reshaped the board (five Elliott nominees plus one further new director, a new chair; corrected 2026-11-24) and within about 18 months free bags, open seating, never-expiring credits and the no-layoff record were gone; the activist cut its directly held shares below 5 % after the share price rose, while keeping about 8.5 % economic exposure (April 2026, corrected 2026-11-24), and the strategy stayed (SWA-02, SWA-06); $2.9B returned to shareholders in 2025 against $97M profit sharing (SWA-11). Board control, not a majority, was enough. Suggests anchoring principles in ownership or statutes (golden share, foundation, customer-elected seat).
- **From the Nike comparison (CS-011):** dual-class control (Swoosh, LLC holds ~79 % of Class A, which elects three-quarters of the board) shields Nike from activists but didn't prevent strategy drift under professional CEOs (NKE-11); $12.1B of buybacks during the decline (NKE-13).
- **From the Haier comparison (CS-013):** employees co-invest in their units and can vote out leaders (HAI-03); the parent is a collective that "has no shareholders", its board chosen by a Staff Assembly, but opaque to outsiders and with large related-party flows (HAI-11).
- **From the Ben & Jerry's comparison (CS-014):** the test of protecting a mission by contract: the 2000 sale agreement created an independent, self-perpetuating board for the social mission (BNJ-08). In 2025–2026 the parent changed eligibility rules and removed most of the board, replaced the CEO and withheld foundation funding (BNJ-10, BNJ-11); in August 2026 the court ruled the board could sue only over its own composition and the foundation not at all (BNJ-09). Earlier: a Vermont-only community share offering (1984) (BNJ-01); now an employee-ownership carve-out explored (BNJ-14). Strong evidence that protections need a party with standing and its own resources (a funded foundation that owns shares, a golden share, steward ownership), not only rights under the buyer's contract.
- **From the Fairphone comparison (CS-015):** impact investors, crowdfunding equity and an employee plan, but in 2025 also 12 % shareholder loans secured on receivables, inventory and IP, negative equity and a going-concern emphasis (FAI-12): transparency and fair sourcing cost money a small company may not have.
- **Evidence from other companies (first pass, not yet compared):** values broke under investor pressure at Southwest (dropped free bags and open seating under an activist investor), Boeing (buybacks over engineering before the 737 MAX crashes) and GitLab (retired its values, including transparency, in May 2026). They held where ownership or the business model protected them: LEGO (family and foundation), Costco (membership fees).
- **Options:** family or foundation ownership; purpose trust; cooperative; membership model; buying out investors; investor agreements that lock in the principles; a combination. Options available in Germany: a veto ("golden") share held by an outside foundation, as Ecosia has used since 2018 (Purpose Foundation model); a foundation as owner (Bosch, Zeiss); the planned "Gesellschaft mit gebundenem Vermögen", a legal form with locked-in assets (framework concept presented by the justice and finance ministries in March 2026; not yet law as far as checked on 2026-10-13).
- **Recommendation:** add a principle on ownership and capital that names which kinds of money fit the framework and how the principles are locked in. From Everlane and Buffer: avoid high-valuation equity with growth expectations and liquidation preferences, keep a way to buy investors out, and anchor the principles in the company's statutes or ownership so they survive the founder. From Patagonia: separate control (held for the purpose) from economic rights, or at least use a purpose-bound legal form such as a benefit corporation; and make the structure's own rules and money flows public.
- **Decision:** decided 2026-11-23
  - Outcome: **the principles must survive a change of control, and the company takes no capital that would override them.**
    - The principles are anchored in the company's ownership or legal form, not only in a founder, a culture or a contract with a buyer. A new owner, investor, board or CEO cannot drop them.
    - Someone independent of the owners can enforce them and has the means to do so.
    - The company takes no capital whose terms require growth or an exit that would override the principles. Investors accept the anchoring.
    - The form is the company's choice (methods stay here): purpose trust and nonprofit (Patagonia), foundation ownership (LEGO, Bosch, Zeiss), a veto share held by an outside foundation (Ecosia), a benefit corporation, Germany's planned asset-locked company form; community rounds, revenue-based finance or impact investors as capital.
  - Outcome per practice:
    - **Adopt:**
      - PAT-01 (steward ownership: control held for the purpose, profits to a nonprofit).
      - PAT-13 (purpose written into the legal form).
      - BUF-10 (buying out investors whose terms point to an exit).
      - BUF-09 (public fundraising terms and equity formula).
      - BNJ-01 (community share offering).
    - **Adapt:**
      - TOY-17 (shielding ownership is the right aim; it must be structural and public, not opaque cross-shareholdings).
      - BUF-11 (founder control must become structural so it survives the founder).
      - FRM-14 (little venture money and a community round; investors must accept the anchoring).
      - LEG-07 (family and foundation ownership; the purpose must be anchored, not only the family's intent).
      - LEG-08, PAT-02 (all flows to owners and the structure's rules are public, under principle 1).
      - HAI-03 (employee co-investment and voice, as one possible enforcing party).
      - SBX-12 (a board body for a stakeholder group only counts if the owners can't dissolve it at will).
      - COS-15 (long-term stance held by culture and results; needs anchoring).
    - **Reject:** EVL-08, EVL-09, BNJ-08, BNJ-10, BNJ-11, SWA-06, GIT-14, SWA-02, BOE-15 (see Explicit rejections).
    - **Park (to FD-07, where profits go):** BOE-03, BOE-14, SWA-11, NKE-13.
    - **Park:** HAI-11 (collective ownership, opaque), BNJ-14 (employee-ownership carve-out, still exploratory), FAI-12 (expensive debt in a small company).
    - **Note only:** SBX-13 (activist-driven CEO change), NKE-11 (control without anchored purpose didn't prevent drift), BNJ-09 (the court ruling that showed the contract unenforceable).
  - Why: principles held by a person, a culture or a buyer's contract were dropped when control changed (Southwest, Ben & Jerry's, Everlane, GitLab); principles anchored in ownership or the legal form held (Patagonia, LEGO). Ben & Jerry's showed that protection needs an independent party with standing and its own means. Capital whose terms required growth or an exit pushed directly against the principles (Everlane, GitLab, Southwest's activist).
  - What we do instead (for rejections): anchor the principles in ownership or the legal form, with an independent enforcer; take only capital that accepts that anchoring; change commitments only in public, with the reason; checks are done by someone the company doesn't choose alone.
  - Framework change: turn the candidate "Ownership and capital" into principle 4: "the principles survive a change of control: anchored in ownership or the legal form, enforceable by someone independent of the owners, and no capital whose terms would override them".
  - Applied in repo: yes (framework commit acabc78 on main, 2026-11-23)
  - Date: 2026-11-23

### FD-02: Employees and suppliers

- **Question:** The framework names employees and suppliers only in its glossary. Do they get their own principle?
- **Practices considered:** TOY-10 (developing people is the route to quality), TOY-11 (long-term supplier partnerships; the 1997 Aisin fire); BUF-02, BUF-03, BUF-07, BUF-14 (Buffer); EVL-03, EVL-07 (Everlane); PAT-08, PAT-09, PAT-10 (Patagonia); GIT-11, GIT-12, GIT-13, GIT-15 (GitLab); LEG-12 (LEGO); COS-09, COS-10, COS-11 (Costco); SBX-07, SBX-08, SBX-09, SBX-10, SBX-12 (Starbucks); BOE-07, BOE-08, BOE-09, BOE-10, BOE-11 (Boeing); SWA-03, SWA-04, SWA-05, SWA-10 (Southwest Airlines); NKE-05, NKE-12 (Nike); TOY-19 (Toyota); HAI-01, HAI-02, HAI-03, HAI-08, HAI-10 (Haier); BNJ-02, BNJ-03, BNJ-05, BNJ-07 (Ben & Jerry's); FAI-05, FAI-14 (Fairphone).
- **From the Buffer comparison (CS-002):** a published pay formula and every salary by name since 2013 (BUF-02, BUF-03), profit sharing of 8–15 % of net profit plus a charity share (BUF-07), fully remote and a 4-day week (BUF-14). Open point: are names needed, or are the formula and bands enough?
- **From the Everlane comparison (CS-010):** factory profiles without audit results, wages or a full supplier list (EVL-03); customer-service staff laid off 4 days after asking for union recognition, with "transparency" used as an argument against the union (EVL-07). Suggests the framework should say how employees get a voice and what is published about suppliers.
- **From the Patagonia comparison (CS-012):** childcare and flextime from early on (PAT-08); in 2024 relocations and layoffs with long severance, and 2 stores unionised after benefit cuts, without voluntary recognition (PAT-09); Fair Trade sewing and supplier labour standards, but living wages in only about a third of apparel-assembly factories (PAT-10). Even a model company didn't give employees a voice before the cuts.
- **From the GitLab comparison (CS-003):** pay formula public in 2018, later restricted to staff and candidates, now offline (GIT-11); a hiring restriction debated in public in 2019, but a critical resignation post was redacted (GIT-12); all-remote and async by default (GIT-13); 2026 cuts of about 14 %, communicated at the point of decision while plans stayed "limited access" (GIT-15).
- **From the LEGO comparison (CS-005):** supplier audits with published non-conformity rates (35 % → 26 % → 20 % of audited high-risk suppliers, 2023–2025), but the 2025 target was loosened without a reason (LEG-12). Employee motivation index and turnover published yearly (LEG-13).
- **From the Costco comparison (CS-006):** the strongest case for employees as part of the model: average US hourly pay about $33, starting pay $20, at least half full-time, 94 % retention, promotion from within, defended as "not altruism" but good business (COS-09). Limits: the founder's CEO-pay line (100–300×) eroded to 283:1 (COS-10); unions accepted but kept at a distance, a contract only after a strike authorisation (COS-11). Suggests: state pay as part of the model, with a published floor and a retention measure; if a pay ratio is set, write it down.
- **From the Starbucks comparison (CS-007):** both sides at once: equity for all partners since 1991 and full tuition (SBX-08), but no first union contract five years after the first vote, a strike and a boycott (SBX-09); a CEO pay ratio of 1,794:1 (SBX-10); warmth mandated through discipline (SBX-07). Suggests benefits without a recognised voice don't prevent conflict.
- **From the Boeing comparison (CS-008):** suppliers squeezed (15 % price cuts, slower payments), then supported and Spirit reacquired (BOE-09); risk pushed onto suppliers on the 787 (BOE-10); a reporting channel with retaliation fears (BOE-07); values drafted by 40 employees (BOE-08); an engineers' contract capping mandatory overtime and creating a joint committee on AI (BOE-11).
- **From the Southwest Airlines comparison (CS-009):** employees first (Kelleher) for five decades (SWA-03); first airline profit sharing, now small relative to shareholder returns (SWA-04); no involuntary layoffs for 53 years, ended in 2025 (SWA-05); highly unionised with large 2024 raises, which protected pay but not jobs or the model (SWA-10).
- **From the Nike comparison (CS-011):** supplier wage-theft remedies disputed or delayed (NKE-05); an internal survey by senior women exposed culture problems, with pay adjusted for about 10 % of staff, while a 2018 pay-equity analysis was halted on counsel's advice without telling staff (NKE-12).
- **From the Haier comparison (CS-013):** pay tied to user results with team profit shares (HAI-02), unit autonomy (HAI-01), but a documented pressure culture (HAI-10) and more than 20,000 who left because they "did not or could not buy into" the system (HAI-08). Suggests: if pay is tied to results, the framework needs a floor and protections.
- **From the Ben & Jerry's comparison (CS-014):** a pay-ratio cap (5:1, then 7:1) abandoned when hiring an outside CEO (BNJ-03); a livable wage since 1995 (BNJ-05); 7.5 % of pre-tax profits to a foundation with employee-guided grants (BNJ-02); farmworker-designed dairy standards (BNJ-07).
- **From the Fairphone comparison (CS-015):** a living-wage bonus for all low-paid workers at supplier factories ($215,000 to 1,650 workers in 2025; "just over $1" per phone) (FAI-05); own staff on a living wage with published people metrics (FAI-14).
- **Evidence from other companies (first pass):** Boeing's recovery includes fairer supplier deals and a new engineers' contract; Starbucks' turnaround runs into an unresolved union contract.
- **Options:** one principle covering both; separate principles; keep in glossary only.
- **Recommendation:** add a principle on how employees are developed and involved, and how suppliers are treated (fair, long-term terms, connected to the published costs).
- **Decision:** decided 2026-11-23
  - Intent: a company is the sum of its people; if the people working towards its goal are well, the company is healthy. (Now the opening of the People principle.)
  - Outcome: **one principle on people, covering employees and suppliers.**
    - Everyone working for the company earns at least a living wage; pay is part of the business model, not charity. Where pay depends on results, the floor still holds.
    - No fixed cap on top pay, but the gap between the highest and the lowest pay is public.
    - Employees can speak up without retaliation, and the company recognises any representation they choose (union, works council).
    - No involuntary layoffs. Under principle 1 this is a commitment: it can only be changed in public, with the reason.
    - Suppliers get fair, long-term terms. A living wage for workers in the supply chain is a public goal, with progress reported.
    - Methods stay here: pay formulas, profit sharing, equity, benefits, pay-ratio levels, audit schemes, living-wage bonuses.
  - Outcome per practice:
    - **Adopt:**
      - TOY-10 (developing people is the route to quality), TOY-11 (long-term supplier partnerships).
      - COS-09 (high pay, promotion from within, as business strategy).
      - BNJ-05 (livable wage), FAI-14 (living wage and people metrics for own staff).
      - SWA-05 (no involuntary layoffs; it held 53 years).
      - FAI-05 (living-wage bonus in the supply chain), PAT-10 (supplier labour standards), BNJ-07 (values-led sourcing).
      - BOE-11 (negotiated overtime caps and a joint committee), BOE-08 (values drafted by employees).
      - PAT-08 (benefits), SBX-08 (equity and tuition), BUF-07 and BNJ-02 (profit sharing): methods consistent with principle 5.
    - **Adapt:**
      - BUF-02, BUF-03, GIT-11 (pay formulas are welcome; names not needed; the pay gap must be public and the living-wage floor met).
      - COS-10, BNJ-03 (pay caps drifted or were dropped; the gap is published instead).
      - COS-11, PAT-09 (unions recognised voluntarily, not after a strike threat or benefit cuts; no involuntary layoffs).
      - BOE-07 (a reporting channel only works without retaliation).
      - BOE-09 (fair supplier terms from the start, not after a crisis).
      - HAI-02 (pay for results above a living-wage floor).
      - NKE-12 (pay-equity checks are completed and reported, not halted).
      - EVL-03, LEG-12 (supplier audit results public; targets changed only with a reason).
      - SWA-04 (profit sharing, weighed against payouts under principle 5).
      - GIT-12 (critical voices aren't redacted).
    - **Reject:** EVL-07, SBX-09, SBX-07, NKE-05, TOY-19, HAI-10, GIT-15 (see Explicit rejections).
    - **Park:** BUF-14, GIT-13 (ways of working), HAI-01 (unit autonomy: FD-05).
    - **Note only:** SBX-10 (an extreme pay ratio; under this principle it would be public), SWA-10 (unions protected pay but not jobs), HAI-08 (people who left a system they didn't buy into).
  - Why: where customer and product focus held, good pay and development were part of the business model (Costco, Toyota). Benefits without a recognised voice didn't prevent conflict (Starbucks, Patagonia, Everlane). Pay tied to results without a floor became a pressure system (Haier). Internal pay caps were dropped (Ben & Jerry's, Costco). Squeezing suppliers came back on the product (Boeing); long-term partnerships paid off (Toyota).
  - What we do instead (for rejections): recognise the representation employees choose; no retaliation; living-wage floor; no involuntary layoffs; fair, long-term supplier terms with supply-chain wages reported.
  - Framework change: replace the candidate "Employees and suppliers" with principle 6 "People", using the points above and this intent.
  - Applied in repo: yes (framework commit 53696ae on main, 2026-11-23)
  - Date: 2026-11-23

### FD-03: Scope of transparency

- **Question:** What is transparent inside the company, what is public, and what stays private, and why?
- **Depends on:** FD-10 (is transparency a goal or a means?). Decide that first; this topic then settles the details (added 2026-11-23).
- **Settled by FD-10 (2026-11-23):** first-order items always public: safety information, commitments and their results, audit outcomes, ownership and governance. Second-order items (price breakdowns, supplier lists, salaries, detailed financials) are public or proven fair by an independent route. Open for this topic: the exact list, and which independent routes count (certification, third-party audit, employee reviews, union agreement).
- **Practices considered:** TOY-02 (stop the line), TOY-08 (little public transparency), TOY-15 (honest reflection on mistakes); BUF-01, BUF-02, BUF-04, BUF-05, BUF-09, BUF-13 (Buffer); EVL-02, EVL-03, EVL-12 (Everlane); PAT-02, PAT-06, PAT-07 (Patagonia); FRM-08, FRM-11, FRM-12, FRM-17 (Framework Computer); GIT-01, GIT-02, GIT-03, GIT-04, GIT-11, GIT-12, GIT-15 (GitLab); LEG-06, LEG-13 (LEGO); COS-07, COS-08 (Costco); SBX-02 (Starbucks); BOE-04, BOE-05, BOE-15 (Boeing); NKE-02, NKE-03, NKE-12 (Nike); TOY-18 (Toyota); HAI-04 (Haier); BNJ-06 (Ben & Jerry's); FAI-02, FAI-03, FAI-13 (Fairphone).
- **From the Buffer comparison (CS-002):** transparency held through a cash crisis (2016), a founder split (2017) and a three-year decline (2020–2023): live metrics, monthly shareholder updates with losses and burn rate, public post-mortems (BUF-01, BUF-04, BUF-05, BUF-13), extended to owners (BUF-09). Two warnings: no shareholder update is listed for 2026, so a habit can stop quietly; and the 2016 layoff post was criticised as oversharing. Suggests adding what is published, how often and in what format.
- **From the Everlane comparison (CS-010):** transparency on what sells (costs, factory stories) but not on wages, audit results, finances or governance (EVL-02, EVL-03); disclosure that started only after the 2020 allegations (EVL-12). The "radical transparency" claims are still on the website after the sale to Shein. Suggests defining a minimum public set, so transparency can't shrink to marketing.
- **From the Patagonia comparison (CS-012):** deep transparency on impact and supply chain, including failures (PAT-06), but none on finances or prices (PAT-07), and only partial on its own ownership structure (PAT-02). Shows that transparency can be deep in one area and absent in another, here for principled rather than marketing reasons.
- **From the Framework Computer comparison (CS-004):** deep transparency on prices and mistakes: firmware shortfalls admitted, delays explained, data incidents disclosed within hours (FRM-11). Open specifications, but a proprietary BIOS (FRM-08). No financial disclosure (FRM-17), the same pattern as Patagonia. The sponsorship list was published only after a 2025 controversy (FRM-12). Lesson: where Framework had a rule set in advance (pricing), it was trusted; where it decided case by case (sponsorships, warranty), it was criticised.
- **From the GitLab comparison (CS-003):** the scale reference: a public handbook of 2,000+ pages (GIT-01), a published list of what is internal or limited access with reasons (GIT-02), public postmortems including a livestreamed recovery (GIT-04). Cautionary: as a listed company the exception list grew to include strategy, pricing plans and reorganisations, and in 2026 Transparency was retired as a value (GIT-03). Shows the format for FD-03's exception list (one page, a reason per item) and the risk that it grows.
- **From the LEGO comparison (CS-005):** a privately owned company that still publishes full financials, margin and employee KPIs (LEG-13), but no product costs. Where it runs the community's own platform (BrickLink), it changed terms abruptly and apologised afterwards (LEG-06).
- **From the Costco comparison (CS-006):** monthly public sales reports, rare among retailers (COS-07); but no guidance, no markup rule in filings, no item costs, no Kirkland supplier list (COS-08).
- **From the Starbucks comparison (CS-007):** leaders named the failure publicly twice, but only after the damage (SBX-02).
- **From the Boeing comparison (CS-008):** the strongest negative evidence: a flight-control system hidden from pilots and test data withheld from the regulator (BOE-04), internal messages released only under pressure (BOE-05). Suggests the minimum public set must include safety-relevant information for users and regulators, without exception.
- **From the Nike comparison (CS-011):** first in its industry to publish all contract factories (2005) (NKE-02), but only after a decade of exposés (NKE-03); wages and audit results still unpublished.
- **From the Toyota comparison (CS-001):** update from finishing the study (2026-11-23): falsified certification across the group in 2022–2024 (Hino since at least 2003, Daihatsu since 1989, Toyota Industries, Toyota itself) (TOY-18). Investigations blamed short development schedules and no psychological safety to challenge superiors. Internal stop-the-line culture didn't reach these departments; outside visibility might have.
- **From the Haier comparison (CS-013):** full internal transparency of unit performance, nothing public (HAI-04).
- **From the Ben & Jerry's comparison (CS-014):** social and environmental reports since the late 1980s, including publishing the auditor's disclaimer on its own social indicators (BNJ-06).
- **From the Fairphone comparison (CS-015):** a private company publishing its full audited accounts, including the going-concern emphasis (FAI-02); supplier and smelter lists with failed audits (FAI-03); honest "fairer" framing (FAI-13).
- **Evidence from other companies (first pass):** GitLab published its handbook but retired transparency as a value.
- **Options:** everything public except a defined list; internal by default with defined public parts; two explicit layers.
- **Recommendation:** two layers. Internal: problems become visible at once and anyone can stop a release. Public: governance, development, pricing and post-mortems. Plus a short list of what stays private (personal data, supplier contracts, security, negotiations) with the reason. The current wording, "all aspects … are transparent and accessible to the public", is stronger than any company studied so far and could hurt people if applied literally. From Everlane: define a minimum public set (finances, ownership, pay formula, supplier list, audit results), so transparency can't be reduced to the parts that sell.
- **Decision:**
  - Outcome per practice:
  - Why:
  - What we do instead (for rejections):
  - Framework change:
  - Applied in repo: no
  - Date:

### FD-04: Pricing logic

- **Question:** How is a fair price set and explained?
- **Depends on:** FD-11, decided 2026-11-23: a published price rule plus proof (own figures or independent audit). This topic settles which rule types are allowed and the customer guarantees (refunds, no charging for unused service, e.g. COS-05, BUF-15) (updated 2026-11-23).
- **Practices considered:** TOY-09 (target costing: market price first, cost made to fit, costs not disclosed); BUF-06, BUF-07, BUF-15, BUF-16 (Buffer); EVL-01, EVL-04, EVL-11 (Everlane); PAT-05, PAT-07 (Patagonia); FRM-01 to FRM-06 (Framework Computer); GIT-06, GIT-08, GIT-09 (GitLab); LEG-09, LEG-10 (LEGO); COS-01, COS-02, COS-03, COS-04, COS-05, COS-06, COS-08, COS-14 (Costco); SBX-04, SBX-05, SBX-15 (Starbucks); SWA-01, SWA-02, SWA-12 (Southwest Airlines); NKE-07, NKE-10 (Nike); HAI-14 (Haier); BNJ-13 (Ben & Jerry's); FAI-01 (Fairphone).
- **From the Buffer comparison (CS-002):** Buffer has published a cost breakdown of its price since 2014 (BUF-06), yet in 2020–2023 raised its Pro plan from $10 to $15 while cutting features and lost customers: the breakdown explained costs but didn't constrain the price. The 2014 version showed profit per $10; today's shows neither profit nor a period. Buffer adds fairness practices: cancelling unused subscriptions and counting lost customers at once (BUF-15), and a free plan for breadth (BUF-16). Profit sharing answers part of where gains go (BUF-07).
- **From the Everlane comparison (CS-010):** the cost-and-markup breakdown per product (EVL-01) became "table stakes" once copied and survived as a claim after the business was sold. "Choose What You Pay" showed 3 prices with what each covers; in a pre-test about 10 % chose more than the lowest (EVL-04). Launched with no discounts, later relied on sales (EVL-11). Suggests outside verification of the breakdown and a rule on discounts.
- **From the Patagonia comparison (CS-012):** no cost breakdowns or financials (PAT-07), but a strong fairness practice: telling customers to buy less and repairing products (PAT-05), comparable to Buffer cancelling unused subscriptions (BUF-15).
- **From the Framework Computer comparison (CS-004):** the strongest case so far, by a different method than a cost breakdown. In December 2025 Framework published three rules: stay transparent, "only increase pricing to cover increases in our costs", and reduce prices "when our costs go back down" (FRM-01). It then kept a public, monthly-updated log with per-GB costs (FRM-02). In September 2026 it kept the rule in the direction that cost it money: automatic refunds and price cuts when cheaper memory arrived (FRM-03). Other practices:
  - In July 2026, when a supplier more than doubled its price, Framework downgraded existing pre-orders at the original price instead of cancelling them. This was transparent but chosen for customers, not by them (FRM-04).
  - Prices are set at the weighted average cost of inventory, and customers are pointed to cheaper RAM elsewhere (FRM-05).
  - In 2025 it published the loss calculation behind pausing products under US tariffs (FRM-06).

  Limit: no financial disclosure (FRM-17), so "only to cover costs" can't be checked from outside.
- **From the GitLab comparison (CS-003):** a written rule for what is free and what is paid: features for individual contributors open, for managers paid (GIT-06). Price increases explained by value added, with a one-year transition price for existing customers (GIT-08). No cost disclosure (GIT-09), like PAT-07 and FRM-17.
- **From the LEGO comparison (CS-005):** no per-product cost disclosure; 2022 increases on existing sets explained only as "increased raw material and operating costs" while net profit rose (LEG-09). CEO claim that the family owner lets LEGO absorb higher sustainable-material costs (LEG-10), not checkable without cost data.
- **From the Costco comparison (CS-006):** the strongest alternative to cost disclosure: a margin ceiling (14 % branded, 15 % private label, an unwritten founder rule) (COS-01) and profit from a membership fee (about half of operating income) that the member can take back at any time (COS-02, COS-05); items not carried unless savings can be passed on (COS-04); symbolic prices held for decades (COS-03). Test case: in 2026 the CEO promised to return tariff-refund value "through lower prices" and to "be transparent", but the results show only "partial reinvestment" and class actions followed (COS-06). Compared with Framework Computer (FRM-03): a windfall should be passed on by a published rule, not by discretion. Recommendation addition: consider a published margin cap as the core rule, combined with a change log.
- **From the Starbucks comparison (CS-007):** a price freeze and a public reference point ("well below CPI") without cost disclosure (SBX-04, SBX-05); a loyalty rework that lowers value for many members, presented as an upgrade (SBX-15).
- **From the Southwest Airlines comparison (CS-009):** a public price promise ("Transfarency", free bags, no change fees) held for decades (SWA-01), then reversed six months after a public investor-day analysis had justified keeping it, with an unpublished new analysis (SWA-02); loyalty and credit terms worsened (SWA-12). Suggests: any change to a public price promise comes with the full analysis and a consultation period.
- **From the Nike comparison (CS-011):** engineered scarcity through SNKRS drops and resale (NKE-07); no cost disclosure, tariff price rises followed by $986M of refunds booked, contested as "double recovery" (NKE-10).
- **From the Haier comparison (CS-013):** no pricing transparency (HAI-14).
- **From the Ben & Jerry's comparison (CS-014):** no pricing transparency (BNJ-13).
- **From the Fairphone comparison (CS-015):** per-phone cost breakdowns for its first two phones, the second showing €9 net profit per phone (FAI-01), then discontinued — like Everlane's, the breakdown faded as the company grew. Suggests making the breakdown a standing practice per product.
- **Evidence from other companies (first pass):** Costco caps markups at about 14–15 %.
- **Options:** cost disclosure only (current draft); disclosure plus a published margin rule; market reference price plus disclosure; plus a rule for where efficiency gains go.
- **Recommendation:** keep cost disclosure, add a published rule (margin cap or range), say where efficiency gains go (lower prices, reinvestment or profit), and say how price changes are announced and explained. From Framework Computer: state the pricing rule in advance for both directions (cost increases passed on only at cost, decreases passed on automatically); keep a dated public log of every price change with its reason; when existing orders are affected, let customers choose (pay, wait, downgrade, cancel). From Buffer: the breakdown always shows profit and the period it covers, and the company doesn't keep charging people who get no value. From Everlane: have the breakdown checked by someone outside the company, and set a rule on discounts.
- **Decision:**
  - Outcome per practice:
  - Why:
  - What we do instead (for rejections):
  - Framework change:
  - Applied in repo: no
  - Date:

### FD-05: Product decisions

- **Question:** Who decides about the product, and how does community input turn into a decision?
- **Depends on:** FD-12 (community-driven development: required or one route?) and FD-13 (public roadmaps). Decide that first; this topic then settles the details (added 2026-11-23).
- **Practices considered:** TOY-04 (go and see), TOY-05 (one chief engineer), TOY-06 (development stays internal), TOY-14 (agreement before decisions); BUF-08, BUF-17 (Buffer); PAT-04 (Patagonia); FRM-08, FRM-09, FRM-10 (Framework Computer); GIT-05, GIT-06, GIT-07, GIT-10 (GitLab); LEG-01, LEG-02, LEG-04, LEG-05 (LEGO); COS-04, COS-13 (Costco); SBX-01 (Starbucks); BOE-01, BOE-13 (Boeing); SWA-07 (Southwest Airlines); NKE-01, NKE-08, NKE-09 (Nike); HAI-01, HAI-05, HAI-06, HAI-08, HAI-12, HAI-13 (Haier); BNJ-12 (Ben & Jerry's); FAI-10, FAI-11 (Fairphone).
- **From the Buffer comparison (CS-002):** a public roadmap where anyone suggests and upvotes, the team decides "if and when", and declined ideas are shown (BUF-08); the reasons behind decisions aren't published. Buffer also cut management layers to keep decisions close to the work (BUF-17). Supports open input with an accountable decider, and adds: publish the reasons.
- **From the Patagonia comparison (CS-012):** product decisions driven by impact and founder conviction, e.g. shrinking the piton business in the early 1970s because pitons damaged rock (PAT-04). Adds a second decision criterion beside community input: impact.
- **From the Framework Computer comparison (CS-004):** community-driven development in hardware through open interfaces. Open Expansion Card and expansion-bay specifications let the community build. Community experiments became products: the OCuLink Dev Kit, and a third-party RISC-V mainboard. The top community requests were all delivered (FRM-09). Specifications are on GitHub, but the BIOS is closed (FRM-08). There is no public roadmap; products are revealed at launch events (FRM-10), which conflicts with principle 4. Possible adaptation: a public list of problems being worked on, without product names or dates.
- **From the GitLab comparison (CS-003):** the cautionary case for community-driven development: public issue tracker, community contributions credited in every release (GIT-05), a decision reversed within a day after community pushback (GIT-10), and twelve published stewardship promises that survived Act 2 (GIT-07). But the mission changed in May 2026 from "everyone can contribute" to "everyone can ship". Suggests writing community input as a commitment, not just a mission statement.
- **From the LEGO comparison (CS-005):** the clearest community-to-product process found: open submissions, a public threshold of 10,000 supporters with time limits, three fixed review rounds a year, about 80 fan sets in 15 years (LEG-01); fan designers paid 1 % of net sales and credited (LEG-02); user hacking allowed rather than fought (LEG-04). Gaps: the Review Board publishes outcomes but not reasons, and fan programmes are reset by the company (LEG-05). Recommendation addition: public threshold and fixed review dates, plus published reasons; pay contributors whose ideas are built, with a defined formula.
- **From the Costco comparison (CS-006):** no formal member-input channel; changes follow complaints (COS-13); product selection follows the price rule (COS-04).
- **From the Starbucks comparison (CS-007):** the second cautionary case: My Starbucks Idea collected about 160,000 ideas and implemented about 300 (2008–2018), then closed without notice, reasons or a public successor (SBX-01). Suggests: community input channels can't be closed without notice, reasons and a replacement.
- **From the Boeing comparison (CS-008):** the oldest working example of customer co-design: eight airlines designed the 777 through a questionnaire, an agreed baseline and a written objectives agreement (BOE-01); 25 years later the FAA panel found Boeing "does not appropriately take pilot input" (BOE-13). Adds a lightweight mechanism: a written objectives agreement with first customers.
- **From the Southwest Airlines comparison (CS-009):** customer views used through unpublished company research, not heard through an input mechanism (SWA-07).
- **From the Nike comparison (CS-011):** the founding mechanism: Bowerman built and tested shoes with his runners (NKE-01); later, a Web3 "co-create" platform (.SWOOSH) was launched and shut down, leaving participants with a proposed "rug pull" class action (NKE-08). Suggests co-creation platforms need exit terms that protect participants.
- **From the Haier comparison (CS-013):** a third route besides one accountable owner (Toyota) and a community threshold (LEGO): thousands of small teams close to users with their own authority (HAI-01), user co-creation with pre-orders as the test (HAI-05), crowdfunding validation at GE Appliances' FirstBuild (HAI-06). Cautions: re-centralised in 2026 when results fell (HAI-12); a takedown against an open-source community integration (HAI-13).
- **From the Ben & Jerry's comparison (CS-014):** limited, mostly promotional customer input (contests, graveyard votes) (BNJ-12).
- **From the Fairphone comparison (CS-015):** open software (bootloader, source code, alternative operating systems) (FAI-10); a community of funders and volunteer helpers, but no formal product-decision input found since the mid-2010s (FAI-11).
- **Evidence from other companies (first pass):** LEGO Ideas: open submissions, a fan support threshold, then an internal review.
- **Options:** community vote; open input and one accountable owner who publishes reasons; open input with a threshold and a review gate.
- **Recommendation:** keep development open (reject TOY-06), add direct observation of users (adopt TOY-04), and name one accountable owner who decides and publishes the reasons (adapt TOY-05), with a defined path from input to decision (adapt TOY-14). From Buffer: publish the reasons for accepting or declining suggestions, not only the status.
- **Decision:**
  - Outcome per practice:
  - Why:
  - What we do instead (for rejections):
  - Framework change:
  - Applied in repo: no
  - Date:

### FD-06: Mechanisms and measures

- **Question:** Which concrete practices and measures carry each principle?
- **Practices considered:** TOY-02 (stop the line), TOY-03 (kaizen on standard work), TOY-07 (visual management, A3); BUF-04, BUF-05, BUF-15 (Buffer); EVL-06 (Everlane); PAT-06 (Patagonia); FRM-02, FRM-03, FRM-13 (Framework Computer); GIT-01, GIT-03, GIT-07 (GitLab); LEG-06, LEG-13 (LEGO); COS-07 (Costco); SBX-03 (Starbucks); BOE-06, BOE-07, BOE-08, BOE-12 (Boeing); SWA-08, SWA-09 (Southwest Airlines); NKE-14 (Nike); TOY-18 (Toyota); HAI-07, HAI-09 (Haier); BNJ-06 (Ben & Jerry's); FAI-07 (Fairphone).
- **From the Buffer comparison (CS-002):** live public metrics (BUF-04), monthly updates (BUF-05) and stricter measures that lower the headline numbers (BUF-15) are working examples of mechanisms and honest measures.
- **From the Everlane comparison (CS-010):** public environmental targets with deadlines and progress reports (EVL-06) are a working mechanism, though not independently verified.
- **From the Patagonia comparison (CS-012):** an annual impact report with public targets that admits misses and abandoned approaches (PAT-06).
- **From the Framework Computer comparison (CS-004):** a dated public price log (FRM-02) and automatic refunds when costs fall (FRM-03) are working mechanisms. The counter-example is the 2026 BIOS fault: warranty exceptions came only after press coverage (FRM-13). Suggests including rules decided in advance for the cases that most often go wrong: price changes, faults the company causes, partner choices.
- **From the GitLab comparison (CS-003):** the strongest evidence that values need mechanisms: Transparency was retired in one memo and the page deleted (GIT-03), while the public handbook (GIT-01) and the stewardship promises (GIT-07), which outsiders rely on, survived. Suggests: any change to the principles goes through a public proposal and comment period.
- **From the LEGO comparison (CS-005):** BrickLink shows the need for a rule on platform changes that affect the community (notice, reasons, consultation) (LEG-06); LEGO's annual KPI reporting is a working mechanism (LEG-13).
- **From the Costco comparison (CS-006):** monthly sales reports as a working public measure (COS-07).
- **From the Starbucks comparison (CS-007):** closing every US store for three hours to retrain (2008) as a visible quality stop (SBX-03).
- **From the Boeing comparison (CS-008):** six safety and quality KPIs named publicly and reviewed by the regulator, but values not published (BOE-06); Speak Up growth in percentages only (BOE-07); bonus 80 % financial, 20 % safety (BOE-12). Suggests: publish measure values on a fixed schedule, not just names.
- **From the Southwest Airlines comparison (CS-009):** outside measures the company doesn't control (DOT complaints, ACSI, J.D. Power) made the effect visible: ACSI fell from 80 to 77 with "trade-offs… between monetization and trust" (SWA-09); a regulatory penalty paid mostly as customer compensation (SWA-08).
- **From the Nike comparison (CS-011):** published sustainability targets with results including misses (NKE-14).
- **From the Haier comparison (CS-013):** an internal unit report built on user value (HAI-07); the model's evidence is mostly self-described, so outside verification is needed before using it as proof (HAI-09).
- **From the Ben & Jerry's comparison (CS-014):** published social audits as a long-running mechanism (BNJ-06).
- **From the Fairphone comparison (CS-015):** impact report with targets and published misses, partly third-party assured (FAI-07).
- **Evidence from other companies (first pass):** GitLab retired its values in one memo; values without mechanisms are easy to drop.
- **Options:** one mechanism and one measure per principle; a separate "practices" section; leave to each implementation.
- **Recommendation:** name at least one mechanism and one measure per principle. Examples: a public decision log, a public cost sheet, a roadmap with voting rules, a changelog, a one-page proposal format, a release gate anyone can trigger; measures such as renewal rate or the share of roadmap items that came from the community.
- **Decision:**
  - Outcome per practice:
  - Why:
  - What we do instead (for rejections):
  - Framework change:
  - Applied in repo: no
  - Date:

### FD-07: Long-term horizon and growth

- **Question:** Does the framework set a time horizon and a limit on growth?
- **Business-history evidence (Boeing, added 2026-11-23):**
  - In July 2011 American Airlines split a record order between Airbus's re-engined A320 and Boeing; within weeks Boeing's board chose a re-engined 737 (the MAX) over an all-new aircraft. Sources: Boeing, 2011-07-20 (https://boeing.mediaroom.com/2011-07-20-Boeing-and-American-Airlines-Agree-on-Order-for-up-to-300-Airplanes); NPR, 2011-07-20 (https://www.npr.org/sections/thetwo-way/2011/07/20/138535143/american-airlines-places-largest-aircraft-order-in-aviation-history); Boeing, 2011-08-30 (https://boeing.mediaroom.com/2011-08-30-Boeing-Launches-737-New-Engine-Family-with-Commitments-for-496-Airplanes-from-Five-Airlines). Analysis: a product decision taken under short-term competitive pressure, which the later MAX problems put in question.
  - In 2001 Boeing moved its headquarters from Seattle to Chicago, "separate from our existing operations". Sources: Boeing, 2001-09-04 (https://boeing.mediaroom.com/2001-09-04-Boeing-Begins-World-Headquarters-Operations-in-Chicago); HistoryLink (https://www.historylink.org/File/5367). Analysis: physical distance between leadership and the product; the current CEO works from the Seattle area again.
- **Also here (from FD-01, 2026-11-23):** where profits go: buybacks and dividends versus reinvestment (BOE-03, BOE-14, SWA-11, NKE-13 parked here).
- **Practices considered:** TOY-12 (long-term philosophy over short-term results), TOY-13 (growth limited by people development); BUF-11, BUF-12 (Buffer); EVL-10 (Everlane); PAT-12 (Patagonia); FRM-07, FRM-15 (Framework Computer); GIT-14 (GitLab); LEG-03, LEG-07, LEG-14 (LEGO); COS-15 (Costco); SBX-06, SBX-14 (Starbucks); BOE-02, BOE-03, BOE-10 (Boeing); SWA-03, SWA-05, SWA-11 (Southwest Airlines); NKE-06, NKE-13 (Nike); TOY-18 (Toyota); BNJ-04 (Ben & Jerry's); FAI-08, FAI-09 (Fairphone).
- **From the Buffer comparison (CS-002):** after 2016–2017 Buffer chose calm, profitable growth and had earlier turned down its largest acquisition offer (BUF-12, BUF-11). Its 2020–2023 decline came from copying a growth playbook that didn't fit its kind of business.
- **From the Everlane comparison (CS-010):** growth pushed faster than a slow supply chain allowed, with quality cuts reported by customers (EVL-10): the opposite of Toyota's growth guardrail and Buffer's calm growth.
- **From the Patagonia comparison (CS-012):** rapid 1980s growth, then a 1991 crisis and 20 % layoffs, then slower growth by choice (PAT-12): the same pattern as Buffer's 2016 crisis.
- **From the Framework Computer comparison (CS-004):** products designed to be kept and upgraded, not replaced: every Laptop 13 generation fits the original chassis (FRM-07). Pre-orders and direct sales tie production to demand (FRM-15).
- **From the GitLab comparison (CS-003):** growth targets as a listed company (about 21 % revenue growth, no full-year GAAP profit) and an AI-driven reorganisation preceded the values change (GIT-14).
- **From the LEGO comparison (CS-005):** the 1998–2004 crisis came from diversification and complexity; the turnaround cut both (LEG-03); outsourcing reversed (LEG-14); ownership without outside investors (LEG-07). Same pattern as Patagonia 1991 and Buffer 2016.
- **From the Costco comparison (CS-006):** two decades of defending wages and prices against Wall Street pressure (COS-15).
- **From the Starbucks comparison (CS-007):** the strongest evidence: growth and efficiency eroded the product twice (2007 "watering down", 2026 "run it like a manufacturing facility") (SBX-14); each turnaround went back to the core (SBX-06). Suggests a growth guardrail tied to a quality measure such as traffic rather than ticket.
- **From the Boeing comparison (CS-008):** "run like a business rather than a great engineering firm" (BOE-02), buybacks over R&D (BOE-03), outsourcing of development risk (BOE-10): the clearest case of short-term financial goals replacing the product principle.
- **From the Southwest Airlines comparison (CS-009):** people-first and no-layoff commitments as a long-term horizon (SWA-03, SWA-05), replaced by shareholder returns under activist pressure (SWA-11).
- **From the Nike comparison (CS-011):** the direct-to-consumer push cut about 30,000 retail partners to about 40 and was later called an "over-rotation" (NKE-06).
- **From the Toyota comparison (CS-001):** update: Daihatsu's committee blamed "management's promotion of short-term development"; Toyota admitted its added OEM work "may have significantly increased (Daihatsu's) burden" (TOY-18). A growth and schedule guardrail must reach subsidiaries and suppliers.
- **From the Ben & Jerry's comparison (CS-014):** a three-part mission giving product, economic and social goals equal weight (BNJ-04).
- **From the Fairphone comparison (CS-015):** 8-year software support after breaking an early promise (FAI-08); repairable design (FAI-09).
- **Evidence from other companies (first pass):** Nike (oversupply, the direct-to-consumer push), Starbucks ("run it like a manufacturing facility").
- **Options:** state a horizon only; horizon plus a growth guardrail; leave out.
- **Recommendation:** state that decisions follow a long-term view even at short-term financial cost, and that growth is limited by how fast the company can develop its people and keep its principles.
- **Decision:** decided 2026-11-23
  - Outcome: **a long-term horizon with three checkable parts.**
    - Decisions take the long view, even at short-term cost (stated as the principle's intent).
    - Growth is limited by the company's ability to keep product quality and develop its people, including at subsidiaries and suppliers.
    - Product and people are funded first; money goes to owners (dividends, buybacks) only after that, and the split is public.
    - Where the product allows, it is built and supported to last; customers aren't pushed to replace it.
    - Methods stay here: quality measures such as traffic rather than ticket or defect rates; payout caps; support periods; repairability scores.
  - Outcome per practice:
    - **Adopt:**
      - TOY-12 (long-term philosophy), TOY-13 (growth limited by people development).
      - BUF-12 (calm, profitable growth), PAT-12 (slower growth by choice), LEG-03 and SBX-06 (back to the core).
      - SWA-03 (people first, then customers, then shareholders).
      - BOE-14 (payouts suspended, capital to the balance sheet and capacity).
      - FRM-07 (upgradeable, backward-compatible products), FAI-08 (long software support), FAI-09 (repairable design).
    - **Adapt:**
      - COS-15 (special dividends are fine once product and people are funded; the split must be public).
      - BNJ-04 (a multi-part mission is fine; product and people come first in the use of money).
      - SWA-05 (no-layoff commitment: details in FD-02).
    - **Reject:** EVL-10, SBX-14, BOE-02, BOE-03, BOE-10, NKE-13, SWA-11, TOY-18 (see Explicit rejections).
    - **Park:** FRM-15 (direct sales and pre-orders: a method), LEG-14 (in-house production: FD-02).
    - **Note only:** NKE-06 (distribution swings: a strategy error rather than a principle question).
    - Already decided under FD-01: BUF-11, GIT-14, LEG-07.
  - Why: customer and product focus was lost through growth that outran quality and people (Starbucks twice, Everlane, Boeing, the Toyota group) and through money leaving while the product was underfunded (Boeing, Nike, Southwest). Companies that kept focus limited growth (Toyota, Buffer, Patagonia after 1991) or protected reinvestment (LEGO, Patagonia). Durable products are product focus over time in concrete form (Framework Computer, Fairphone, Patagonia).
  - What we do instead (for rejections): growth limited by quality and people development, also at subsidiaries and suppliers; product and people funded before payouts, with the split public.
  - Framework change: turn the candidate "Long-term horizon and growth" into principle 5 with the four points above.
  - Applied in repo: yes (framework commit 1647038 on main, 2026-11-23)
  - Date: 2026-11-23

### FD-08: Environmental and supply-chain impact

- **Question:** Does the framework cover environmental and social impact along the supply chain, and how is it made verifiable?
- **Practices considered:** EVL-03 (factory profiles without full audit results), EVL-05 (Black Friday Fund for factory workers), EVL-06 (environmental targets with public deadlines); PAT-03, PAT-04, PAT-05, PAT-06, PAT-10 (Patagonia); FRM-07, FRM-16 (Framework Computer); LEG-10, LEG-11, LEG-12 (LEGO); COS-12 (Costco); SBX-11 (Starbucks); NKE-02, NKE-03, NKE-04, NKE-05, NKE-14 (Nike); BNJ-02, BNJ-07 (Ben & Jerry's); FAI-03, FAI-04, FAI-05, FAI-06, FAI-07, FAI-09 (Fairphone).
- **From the Patagonia comparison (CS-012):** 1 % of sales given since the 1980s, profit or not (PAT-03); impact as a product criterion (PAT-04); buy less and repair (PAT-05); impact reporting that includes failures (PAT-06); supplier labour standards (PAT-10). The opposite of Everlane: impact claims backed by reporting, including bad news.
- **From the Framework Computer comparison (CS-004):** repairability and upgradeability as the product, with iFixit 10/10 (FRM-07). Honest claims ("We are not Sustainable. And neither is any other device maker.") and a Fraunhofer IZM life-cycle analysis, but no supplier list, conflict-minerals report, labour audit or take-back programme (FRM-16). EU rules (right to repair from July 2026, removable batteries from February 2027) are making parts of this mandatory.
- **From the LEGO comparison (CS-005):** targets and yearly reporting, an admitted failure (recycled-PET brick), but a headline "52 % renewable/recycled" figure based on mass-balance accounting that critics contest (LEG-11); supplier audit rates (LEG-12).
- **From the Costco comparison (CS-006):** vertical integration to hold a symbolic price (a $450M poultry complex) led to animal-welfare disputes; audits rely mainly on suppliers (COS-12). A price promise can push costs onto animals and suppliers.
- **From the Starbucks comparison (CS-007):** third-party-verified sourcing standard with published shares including declines, but "100 % ethically sourced" marketing is litigated (SBX-11).
- **From the Nike comparison (CS-011):** the pioneer of supplier disclosure: full factory list since 2005, now a quarterly map (NKE-02); private regulation with self-reported compliance (90 % vs a 100 % target) and audits that 2026 reporting calls "sham" (NKE-04); remedy disputes (NKE-05). With Patagonia and Framework Computer, shows a gradient: names published → impact reported → wages and audits still missing everywhere.
- **From the Ben & Jerry's comparison (CS-014):** values-led sourcing including farmworker-designed standards (Milk with Dignity) (BNJ-07) and a fixed profit share for the community (BNJ-02).
- **From the Fairphone comparison (CS-015):** the third company this topic needed, and the most complete: supplier and smelter lists including failed audits (FAI-03), the verification level stated next to every material claim, with much of the "fair" share openly based on credits and mass balance (FAI-04), a living-wage bonus at suppliers (FAI-05), e-waste neutrality with a contestable method (FAI-06), targets and misses published (FAI-07). Recommendation addition: require the method and verification level next to every impact claim, and count only what goes beyond legal obligations.
- **Evidence so far (updated 2026-11-23):** five companies with substantial practices: Everlane (cautionary: claims without audit results), Patagonia, Nike (names published, wages and audits not), Framework Computer (honest claims, thin supply-chain data), Fairphone (most complete). Supporting cases: LEGO, Costco, Starbucks, Ben & Jerry's. A gradient emerges: supplier names → impact reported with misses → audit outcomes and verification levels → wages. Almost no company publishes wages at suppliers; Fairphone pays a living-wage bonus and states its cost (about $1 per phone).
- **Options:** leave it out and keep the framework about openness and community; add a separate principle with targets; cover it only as a transparency requirement (publish impact and supplier data, independently verified).
- **Recommendation (updated 2026-11-23):** cover it as a transparency requirement, not a separate set of targets. Concretely:
  - **Publish:** the supplier list, with audit outcomes including failures (adopt NKE-02, FAI-03).
  - **Report:** impact against targets, including misses (adopt PAT-06, FAI-07, NKE-14).
  - **Label every claim:** state the method and verification level next to each impact number (credits, mass balance, physical content; third-party, second-party or documents only). Count only what goes beyond legal obligations (adapt FAI-04, FAI-06, LEG-11).
  - **Supplier workers:** pay a living-wage contribution or publish why not (adopt FAI-05).
  - **Language:** say "fairer", never claim "fair" or "100 %" (adopt FAI-13; reject EVL-02, SBX-11 marketing).
  - **Optional:** a fixed giving share tied to sales or pre-tax profit, held by a body with its own funds (PAT-03, BNJ-02, BNJ-11).
- **Decision:**
  - Outcome per practice:
  - Why:
  - What we do instead (for rejections):
  - Framework change:
  - Applied in repo: no
  - Date:

### FD-09: Core goal and scope

- **Question:** What is the framework for? The draft is titled "Open and Community-Driven Business Operations and Product Development". The stated aim (2026-11-23) is broader: a good company with a real customer and product focus. Is openness the goal, one route to it, or one part of it?
- **Evidence across 15 companies:**
  - **Customer and product focus held** where it was built into the business model or ownership. Examples: Costco's fee model, LEGO's and Patagonia's ownership, Toyota's production system, Framework Computer's repairability.
  - **It was lost through growth and efficiency drives,** not through a lack of openness. Examples: Starbucks twice, Nike, Boeing, LEGO before 2004, Buffer 2020–23, Toyota's group scandals.
  - **Openness helped most where it made a promise checkable** by the people it affected. Examples: Framework Computer's price log, Fairphone's supplier audits, GitLab's open-source promises, Ben & Jerry's social audits.
- **Options:** keep the current scope (openness and community); widen to "customer- and product-focused business", with openness as one principle among several (ownership, growth limits, employees, pricing rules); or split into a core and optional modules.
- **Recommendation:** widen the goal to customer and product focus, and keep openness as a means wherever it makes commitments checkable. This would also justify adding principles on ownership (FD-01), employees (FD-02) and growth (FD-07), which the evidence supports more strongly than some of the draft's current principles. Renaming the framework follows from this decision.
- **Decision:** decided 2026-11-23
  - Outcome: **widen.** The framework's core goal is a business with a real customer and product focus that keeps it over time. Openness and community involvement stay, but as means (to make commitments checkable and to stay close to users), not as the goal. Ownership and capital (FD-01), employees and suppliers (FD-02) and long-term horizon and growth limits (FD-07) become candidate principles in their own right.
  - Why: across 15 companies, customer and product focus held where it was built into the business model or ownership and was lost through growth and efficiency drives; openness mattered most where it made specific promises checkable. Several of the most customer-focused companies studied are not especially open.
  - Framework change: restate the purpose at the top of the framework README; the existing four principles are reviewed under FD-10 to FD-13; new principles to be drafted from FD-01, FD-02 and FD-07. **Name:** keep the current title for now and choose a new one once FD-10 to FD-13 are decided (2026-11-23). **Renamed 2026-11-23:** "Framework for People-First, Customer- and Product-Focused Businesses". Reason: no catchy name; state what it is, like the original title.
  - Applied in repo: yes (framework commit 9c9e968 on main, 2026-11-23; was c181b56 before re-authoring)
  - Date: 2026-11-23
### FD-10: Transparency — goal or means?

- **Question:** The draft's first principle says "all aspects … are transparent and accessible to the public". Is transparency a value in itself, or a tool for keeping promises to customers and others checkable? How much of it actually serves customers and product?
- **Evidence for transparency as a core principle:**
  - Toyota's two biggest failures happened where it wasn't transparent to outsiders (TOY-08, TOY-18).
  - Boeing's concealment led to fatal crashes (BOE-04).
  - Buffer, Fairphone and GitLab's handbook show deep openness can be sustained (BUF-01, FAI-02, FAI-03, GIT-01).
  - Nike's factory list improved supply-chain accountability (NKE-02).
- **Evidence against transparency as the core:**
  - Several of the most customer-focused companies are fairly closed: Costco (COS-08), Toyota (TOY-08) and LEGO (LEG-09). Patagonia is open on impact but closed on finances (PAT-07).
  - Transparency held by values alone was dropped in one memo (GIT-03), or used as marketing (EVL-02).
  - Publishing every salary by name caused harm (BUF-02).
- **What the evidence suggests:** transparency works when it is aimed. It makes specific commitments checkable by the people affected: prices (FRM-02), suppliers (FAI-03), safety (BOE-04), the mission (BNJ-06). Blanket openness is rare and doesn't protect values on its own.
- **Options:** keep "all aspects public" with a short exception list (FD-03's current recommendation); make transparency a means: "every commitment to customers, employees and suppliers is published and checkable"; or drop it as a principle and require it only inside other principles.
- **Recommendation:** the second option. Make transparency the way commitments are kept, with a minimum public set (prices or price rules, safety-relevant information, supplier lists, the company's own commitments and how they're measured). Decide this before FD-03, which then becomes "what exactly is in the minimum set".
- **Decision:** decided 2026-11-23
  - Outcome: **transparency is a means, not a goal.** Disclosure is required where it is foundational ("first-order"); elsewhere it is one way among others to prove a commitment is kept.
    - **First-order, always public (core minimum set):**
      - safety-relevant information for users and the public;
      - the company's commitments (its mission, its promises) and their results, including misses;
      - the outcomes of audits and checks on those commitments;
      - ownership and governance: who owns and controls the company, and the rules that protect the mission.
    - **Second-order, public *or* proven another way:** price breakdowns, supplier lists, salaries and detailed financials. These don't have to be published if the fairness they would show is proven otherwise. Examples: a published price rule, certification or third-party audit of suppliers and emissions, independent employee reviews, or a union agreement.
  - Outcome per practice:
    - **Adopt:** TOY-02 (internal stop-the-line), TOY-15 (honest reflection), FRM-11 (admitting shortfalls and incidents), BNJ-06 (social audits incl. the auditor's disclaimer).
    - **Adapt:**
      - BUF-01 ("default to transparency" becomes "transparency where it proves a commitment").
      - TOY-08 (acceptable if the minimum set is public).
      - NKE-02 and FAI-03 (supplier lists optional; audit outcomes required).
      - FAI-02 (full accounts welcome, not required).
    - **Reject:**
      - BOE-04: hiding safety-relevant information.
      - GIT-03: principles held only as internal values that can be retired without a public record.
    - **Not a transparency question any more**, moved to FD-11: PAT-07, FRM-17, GIT-09, COS-08 (closed costs and finances). They are no longer rejection candidates on transparency grounds.
  - Why: the most customer-focused companies studied are not the most open (Costco, Toyota, LEGO); transparency mattered where it made specific commitments checkable (prices, suppliers, safety, the mission); harm came from hiding safety information (Boeing) and from values that could be dropped silently (GitLab), not from keeping costs or salaries private. Publishing everything can also harm people (BUF-02).
  - What we do instead (for rejections): BOE-04 — safety-relevant information is always public. GIT-03 — the company's commitments are published, with their results, and any change to them is made in public.
  - Framework change: rewrite principle 1 "Transparency and accountability" from "all aspects … are transparent and accessible to the public" to "every commitment is public and checkable: safety information, commitments and their results, audit outcomes, ownership and governance are always public; other information (costs, suppliers, pay, financials) is published or its fairness is proven by an independent route". FD-03 now settles the exact minimum set and what counts as an independent route.
  - Applied in repo: yes (framework commit 9c9e968 on main, 2026-11-23; was c181b56 before re-authoring)
  - Date: 2026-11-23
### FD-11: Fair prices — cost disclosure or a price rule?

- **Question:** The draft's third principle requires disclosing all costs so the price can be justified. Is that what makes prices fair, or is a published rule (a margin cap, a pass-through rule, a fee model) enough or better?
- **Evidence for cost disclosure:**
  - Buffer, Everlane and Fairphone published breakdowns (BUF-06, EVL-01, FAI-01).
  - Framework Computer's per-unit costs made its rules checkable (FRM-02).
- **Evidence against it as the core:**
  - Breakdowns faded as companies grew (EVL-01, FAI-01) or didn't stop price rises (BUF-06).
  - Costco treats customers fairly without any cost disclosure: a markup cap, profit from a refundable fee, items not carried unless savings can be passed on (COS-01, COS-02, COS-04, COS-05).
  - Southwest kept a public fairness promise for decades without cost data, until the owner changed (SWA-01, SWA-02).
  - Framework Computer's strongest practice is its rule set in advance in both directions, not the costs themselves (FRM-01, FRM-03).
- **What the evidence suggests:** the rule decides fairness; disclosure makes the rule checkable. Neither works without the other at scale: a rule without data relies on trust (COS-06), and data without a rule doesn't constrain (BUF-06).
- **Options:** cost disclosure only (draft); a published price rule only; a published rule plus enough cost data to check it; a fee model.
- **Recommendation:** a published price rule (margin cap or pass-through in both directions), plus the cost data needed to check that rule, plus fairness guarantees (refunds, no charging for unused service). Replace "disclose all costs" with "publish the rule and the numbers that prove you follow it". FD-04 then decides the details.
- **Decision:** decided 2026-11-23
  - Outcome: **fair prices come from a published price rule that is provably kept, not from disclosing all costs.**
    - The company publishes a price rule set in advance (for example a margin cap, cost changes passed on in both directions, or profit from a refundable fee instead of the goods).
    - It proves the rule is kept by **either route**: its own published figures (e.g. average margin, cost changes) **or** an independent audit whose result is public. Consistent with FD-10: cost breakdowns are second-order.
    - A full cost breakdown is welcome but not required.
    - Customer guarantees (refunds, no charging for unused service) are **left to FD-04**, not part of this principle.
  - Outcome per practice:
    - **Adopt:**
      - FRM-01 (pricing rules set in advance, both directions).
      - FRM-03 (rule applied automatically when costs fall).
      - SWA-01 (a public price promise).
    - **Adapt:**
      - FRM-02 (public price log with per-unit costs: one proof route, not required).
      - COS-01 (the markup cap; it must be published).
      - COS-02 (a fee model is one allowed type of rule; details in FD-04).
      - BUF-06, EVL-01, FAI-01 (cost breakdowns: one proof route, not required; they don't replace a rule).
      - PAT-07, GIT-09, LEG-09, SBX-05, NKE-10, BNJ-13, HAI-14, FRM-17, COS-08 (closed costs and finances): acceptable if a published rule and proof exist. Not rejected.
    - **Park (to FD-04):** COS-05 (refundable fee and generous returns: a customer guarantee).
  - Why: cost breakdowns faded with growth or didn't stop price rises (EVL-01, FAI-01, BUF-06). The companies that treated customers fairly on price over time did so through a rule (Costco, Framework Computer, Southwest until its owner changed). A rule without proof rests on trust (COS-06); proof without a rule doesn't constrain (BUF-06).
  - Framework change: rewrite principle 3 "Fair pricing" from "disclose all costs" to "publish the price rule and prove it is kept — by own figures or an independent audit". FD-04 settles the rule types and customer guarantees.
  - Applied in repo: yes (framework commit a828cea on main, 2026-11-23)
  - Date: 2026-11-23

### FD-12: Community-driven development — required, or one way to stay close to customers?

- **Question:** The draft's second principle makes community-driven development central. The evidence shows several routes to customer focus. Which should the framework require?
- **Evidence for community-driven development:**
  - LEGO Ideas (LEG-01), Boeing's 777 co-design (BOE-01), Bowerman's runners (NKE-01), Haier and FirstBuild pre-orders (HAI-05, HAI-06), Framework's open interfaces (FRM-09), GitLab contributions (GIT-05).
- **Evidence for other routes:**
  - Toyota's "go and see" and one accountable chief engineer, with development kept internal (TOY-04, TOY-05, TOY-06).
  - Costco's buyers curate under a price rule (COS-04).
  - Patagonia decides by impact and founder conviction (PAT-04).
- **Cautionary:** community platforms closed or withdrawn without commitment (SBX-01, NKE-08); a mission changed from "everyone can contribute" (GIT-03).
- **What the evidence suggests:** what matters is staying close to real users, with a clear path from their input to a decision and a visible outcome. Community input is one strong way to do that, not the only one.
- **Options:** keep community-driven development as a requirement; require "closeness to users" with a menu of mechanisms (community input with a gate, direct observation, co-design with lead customers, pre-orders), each with published reasons for decisions; drop it.
- **Recommendation:** the second option. Require a defined path from user input to a decision with published reasons, and let the mechanism vary. FD-05 then decides who owns the decision.
- **Decision:** decided 2026-11-23
  - Outcome: **closeness to users is required; community-driven development is one way to get there, not a requirement.**
    - The company stays close to the people who use its products. The method is up to the company: community input, direct observation, co-design with key customers, pre-orders.
    - User input has a defined path to decisions, and the reasons for those decisions are public, including why something was turned down.
  - Outcome per practice:
    - **Adopt:**
      - TOY-04 (go and see).
      - BOE-01 (co-design with an agreed baseline and a written agreement).
      - NKE-01 (users shape and test prototypes).
      - HAI-05, HAI-06 (co-creation tested by pre-orders).
      - FRM-09 (open interfaces; community experiments become products).
      - GIT-05 (public issue tracker; contributions credited).
    - **Adapt:**
      - LEG-01 (keep the threshold and review rounds; publish the reasons for decisions).
      - BUF-08 (a public roadmap is one possible path; whether it's needed is FD-13).
      - SBX-01 (an input channel is part of the path: closing it is a change made in public, with the reason and a successor).
      - TOY-06 (internal development is acceptable when closeness to users comes another way).
  - Why: the most customer-focused companies include ones without community input (Toyota, Costco). Where community input worked, there was a clear path from input to decision (LEGO's threshold, Boeing's written agreement, Haier's pre-orders); its main weakness was missing reasons (LEGO). The failures came from abandoning users (SBX-01, NKE-08, BOE-13, HAI-13), not from too little openness.
  - Framework change: rewrite principle 2 from "community-driven product development" to "closeness to users: the company stays close to the people who use its products; user input has a defined path to decisions, and the reasons for those decisions are public". FD-05 settles who owns product decisions.
  - Applied in repo: yes (framework commit 78ceefc on main, 2026-11-23)
  - Date: 2026-11-23

### FD-13: Public roadmaps and task boards — needed?

- **Question:** The draft's fourth principle requires public task boards and roadmaps. Does the evidence support that?
- **Evidence:**
  - Buffer's public roadmap with upvotes (BUF-08) and GitLab's public issue tracker (GIT-05) worked for software.
  - Framework Computer has no roadmap, for hardware lead-time and supplier reasons, and its users ask for one (FRM-10).
  - LEGO, Costco and Toyota have none and are customer-focused.
- **Options:** require public roadmaps and boards; require a public list of problems being worked on, without dates or product names; make it optional, depending on the product.
- **Recommendation:** a public list of the problems being worked on and the reasons behind decisions, not full task boards. This keeps users informed without pre-announcing products. Fold it into FD-12's path from input to decision.
- **Decision:** decided 2026-11-23
  - Outcome: **drop principle 4.** The framework has no project-management principle. FD-12 (a defined path from user input to decisions, with public reasons) covers what principle 4 was meant to achieve. Public roadmaps, task boards or problem lists are methods a company may choose; they suit software better than hardware.
  - Outcome per practice:
    - **Adapt:** BUF-08, GIT-05 (public roadmap and issue tracker: optional methods, already counted under FD-12).
    - **Note only:** FRM-10 (no public roadmap is acceptable; community requests still shape products). Who decides stays with FD-05.
  - Why: public roadmaps worked for software (Buffer, GitLab), where plans change cheaply. Customer-focused companies without one (Framework Computer, LEGO, Costco, Toyota) show it isn't needed, and no failure in the studies came from a missing roadmap. Under the "what, not how" rule, a roadmap is a method.
  - Framework change: remove principle 4 "Open project management". The framework now has three principles plus the candidate principles.
  - Applied in repo: yes (framework commit 326007b on main, 2026-11-23)
  - Date: 2026-11-23

## Framework snapshot (as read on 2026-11-23, commit 5b01bdc)

Principle numbers in decisions above refer to the order at the time of each decision. Current order (reordered 2026-11-23: people first, the two cross-cutting principles last):

- **Goal:** a business with a real customer and product focus that keeps it over time; openness and community involvement are means (FD-09).
1. **People** (FD-02): living wage, public pay gap, recognised representation, no involuntary layoffs, fair long-term supplier terms.
2. **Closeness to users** (FD-12): user input has a defined path to decisions, with public reasons.
3. **Fair pricing** (FD-11): a published price rule, proven to be kept; full cost disclosure not required.
4. **Long-term horizon** (FD-07): growth limited by quality and people; product and people funded before payouts; durable products where the product allows.
5. **Transparency and accountability** (FD-10): every commitment public and checkable; first-order always public, second-order public or proven independently.
6. **Principles that survive a change of control** (FD-01): anchored in ownership or legal form, independent enforcer, no capital that overrides them.
- **Dropped:** open project management (FD-13).
- **Name:** "Framework for People-First, Customer- and Product-Focused Businesses" (renamed 2026-11-23, FD-09; descriptive, like the original). Repo: https://github.com/Maxi-Teme/Framework-for-People-First-Customer-and-Product-Focused-Businesses
- **Other:** methods kept out of the framework ("what, not how"); implementation strategies removed; benefits rewritten; no progress markers in the README; changes recorded in the repo's CHANGELOG.md.

## Framework snapshot (as read on 2026-10-12)

Source: [GitHub, Framework for Open and Community-Driven Business Operations and Product Development (renamed 2026-11-23)](https://github.com/Maxi-Teme/Framework-for-People-First-Customer-and-Product-Focused-Businesses) (README, 4 commits; lists sited.io as an implementation).

- **Principles:** 1. Transparency and accountability; 2. Community-driven product development; 3. Fair and transparent pricing (disclose all costs so the price can be justified); 4. Open project management (public task boards and roadmaps).
- **Implementation strategies:** communication and engagement; documentation and accessibility; open project management tools; continuous improvement.
- **Benefits:** trust and reputation; market responsiveness and innovation; collaboration and efficiency.
- **Stakeholder glossary:** customers, community members, investors, employees, suppliers and partners, regulators, competitors, media and public opinion.

When the framework README changes, add a new snapshot with its date; comparisons say which snapshot they used.

## Sources (first pass, 2026-10-12)

Toyota, Buffer, Everlane, Patagonia, Framework Computer, GitLab, LEGO, Costco, Starbucks, Boeing, Southwest Airlines, Nike, Toyota, Haier, Ben & Jerry's and Fairphone sources are listed at the end of each comparison in `comparisons/`. First-pass evidence for other companies:

| # | Outlet | Title | Link |
|---|---|---|---|
| 1 | Buffer | Open metrics / transparency page | https://buffer.com/transparency |
| 2 | Notebookcheck | Framework nearly doubles Laptop 13 Pro RAM prices overnight as CEO warns supplier costs put company at financial risk | https://www.notebookcheck.net/Framework-nearly-doubles-Laptop-13-Pro-RAM-prices-overnight-as-CEO-warns-supplier-costs-put-company-at-financial-risk.1349842.0.html |
| 3 | Brickset | LEGO achieves record revenue and increased profit in 1H 2026 | https://brickset.com/article/134199/lego-achieves-record-revenue-and-increased-profit-in-1h-2026 |
| 4 | 24/7 Wall St. | Costco Q4 2026: $95.7B revenue, 9.4% comp sales growth | https://247wallst.com/cards/costco-q4-2026-earnings-cost-01m3akd6z57rtsq2hhaynthvrh |
| 5 | Yahoo Finance | Two Years In, Starbucks' CEO Niccol Has Won Back Customers. Now Wall Street Wants Margins | https://finance.yahoo.com/markets/stocks/articles/two-years-starbucks-sbux-ceo-215502629.html |
| 6 | Fortune | Starbucks CEO Brian Niccol: "run it like a manufacturing facility" (2026-03-23) | https://fortune.com/2026/03/23/starbucks-ceo-brian-niccol-back-to-starbucks-ran-like-manufacturing-facility |
| 7 | Starbucks Investor Relations | Q4 and Full Fiscal Year 2026 Results Conference Call (29 Oct 2026) | https://investor.starbucks.com/news/financial-releases/news-details/2026/Starbucks-Announces-Q4-and-Full-Fiscal-Year-2026-Results-Conference-Call/default.aspx |
| 8 | Fortune | How Kelly Ortberg is rebuilding Boeing from the inside out | https://fortune.com/2026/06/01/kelly-ortberg-boeing-innovation-aircraft/ |
| 9 | Leeham News | Boeing Avoids Strike as SPEEA Engineers and Technicians Approve New Contracts | https://leehamnews.com/2026/10/01/boeing-avoids-strike-as-speea-engineers-and-technicians-approve-new-contracts/ |
| 10 | CNBC | Southwest ends open seating after 54 years | https://www.cnbc.com/2026/01/28/southwest-airlines-ends-open-seating.html |
| 11 | Aviation A2Z | Southwest Airlines Turns a Corner as Activist Investor Elliott Walks Away | https://aviationa2z.com/index.php/2026/02/11/southwest-airlines-turns-a-corner-as-activist-investor-elliott-walks-away/ |
| 12 | Retail Dive | Following Shein sale, Everlane founder launches new brand | https://www.retaildive.com/news/shein-sale-everlane-founder-launches-new-brand-still-radical/821167/ |
| 13 | GitLab | GitLab Act 2 (Bill Staples, 2026-05-11) | https://about.gitlab.com/blog/gitlab-act-2/ |
| 14 | Bakery&Snacks | Ben & Jerry's vs Unilever lawsuit reaches crucial stage (2026-07-01) | https://www.bakeryandsnacks.com/Article/2026/07/01/ben-jerrys-vs-unilever-lawsuit-reaches-crucial-stage/ |

FD-01 German options: Purpose Economy, "Ecosia" (https://purpose-economy.org/en/companies/ecosia/); BMJV press release 2026-03-04, "Eine neue Rechtsform für nachhaltiges Unternehmertum" (https://www.bmjv.de/SharedDocs/Pressemitteilungen/DE/2026/0304_GMGV.html).

Buffer's 2018 investor buyout, Costco's markup cap, Everlane's per-product cost breakdowns and Patagonia's 2022 ownership change come from general knowledge; the relevant studies should add sources.
