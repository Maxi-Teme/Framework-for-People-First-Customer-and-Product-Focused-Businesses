# Framework Computer and the framework: comparison

| Field | Value |
|---|---|
| Study ID | CS-004 |
| Practice IDs | FRM-01 to FRM-17 |
| Framework version compared | snapshot of 2026-10-12 (see `../decisions.md`) |
| Written | 2026-11-23 |
| Last updated | 2026-11-23 |
| Sources | listed under *Sources* at the end of this file (source numbers in brackets) |

Area codes, fit values and how this file feeds decisions: see `../README.md`.

## 1. Summary

Framework **confirms** the framework's pricing principle more convincingly than any company studied so far, though by a different method. It doesn't publish a full cost breakdown. Instead it runs a public log of how its costs change its prices, under rules it set in advance: prices go up only to cover costs, and come down when costs fall. In September 2026 it kept that rule in the direction that cost it money, with automatic refunds. Framework also confirms community-driven product development in hardware: open specifications and interfaces that let the community build, and community requests that became products.

It **adds** what the framework doesn't cover: rules for price changes in both directions, pointing customers to cheaper suppliers, explaining losses (not just prices), honest environmental claims ("We are not Sustainable"), and a small community investment round.

It **differs** from the framework in two places. There is no public roadmap, which goes against principle 4. And there is no financial disclosure of revenue, profit or headcount. Its transparency was also reactive at the two moments that hurt most: sponsorships in 2025 and the bricked-board warranty in 2026. Lesson for FD-03 and FD-06: where Framework had a rule in advance (pricing), it was trusted; where it decided case by case, it was criticised.

## 2. Overview

| ID | Framework Computer practice | Area | Fit | Decision topic |
|---|---|---|---|---|
| FRM-01 | Public pricing rules set in advance: increase only to cover costs, reduce when costs fall | PR, TR | partial | FD-04 |
| FRM-02 | Running public price log, updated monthly, with per-unit costs and a livestream Q&A | PR, TR | partial | FD-04, FD-06 |
| FRM-03 | Price cuts and refunds applied automatically when costs fall; pre-order prices honoured | PR | gap | FD-04, FD-06 |
| FRM-04 | Pre-orders downgraded at the original price when a supplier doubled its price, instead of cancelling or charging more | PR, CO | gap | FD-04 |
| FRM-05 | Pricing at weighted average inventory cost, and pointing customers to cheaper parts elsewhere | PR | gap | FD-04 |
| FRM-06 | Publishing the loss calculation behind a price or product decision (2025 tariffs) | PR, TR | partial | FD-04 |
| FRM-07 | Repairability and upgradeability as the product: backward-compatible boards, parts marketplace, reuse | PD, EN | gap | FD-07, FD-08 |
| FRM-08 | Open specifications and reference designs on GitHub; core BIOS stays proprietary | TR, PD | partial | FD-03, FD-05 |
| FRM-09 | Open interfaces let the community build modules; community experiments become products | PD | match | FD-05 |
| FRM-10 | Community requests shape products, but no public roadmap; reveals at launch events | PM, PD | differs | FD-05 |
| FRM-11 | Public admission of shortfalls and delays, with causes; data incidents disclosed within hours | TR, CO | match | FD-03 |
| FRM-12 | Sponsorship list published only after a controversy; "big tent" neutrality on partners' politics | TR, CO | partial | FD-03 |
| FRM-13 | Warranty exceptions for a self-caused fault decided only after press coverage | CO, CI | partial | FD-06 |
| FRM-14 | Little venture money ("raise as little as possible"), plus a $1M community round | OW | gap | FD-01 |
| FRM-15 | Direct-to-consumer only, with pre-orders financing production | OW, LT | gap | FD-07 |
| FRM-16 | Honest environmental claims and a life-cycle analysis, but no supplier list, audits or take-back | EN, SU | partial | FD-08 |
| FRM-17 | No financial disclosure: no revenue, profit, headcount or cap table | TR, OW | differs | FD-03 |

Count: 2 match, 7 partial, 6 gap, 2 differs.

## 3. Practices in detail

### FRM-01: Public pricing rules set in advance

- **What the company does:** When memory prices started rising in December 2025, Patel published three principles: "We are going to stay transparent." "We won't use this as an excuse to be extractive. We'll only increase pricing to cover increases in our costs." "When our costs go back down… we'll reduce our pricing." [1]
- **Why it works for them:** The cause was outside its control (an industry-wide memory shortage) and easy for customers to check against press coverage. Customers are technical and follow component prices.
- **Fit:** partial. The framework asks for cost disclosure "so the price can be justified". Framework doesn't disclose its full costs, but it makes the *rule* for its prices public. That rule is what made the disclosure checkable, and Buffer and Everlane lacked it (FD-04).
- **Transfer:** a small company can publish a pricing rule in three sentences before it ever publishes a cost sheet.

### FRM-02: Running public price log

- **What the company does:** One blog post, updated in place from December 2025 to November 2026, records each change with its reason. It gives per-GB costs ($10/GB in December 2025, $12–16 in February, $13–18 in March 2026) and compares them with Apple's $25/GB. A livestream Q&A was held in February 2026. [1, 40]
- **Why it works for them:** Price changes were frequent, so a single explanation would have gone stale within weeks.
- **Fit:** partial. The framework requires disclosure but says nothing about format or frequency. A dated, cumulative log is a concrete mechanism (FD-06).
- **Transfer:** keep one public page per price, with a dated history of changes and reasons.

### FRM-03: Automatic price cuts and refunds when costs fall

- **What the company does:** In September 2026 a cheaper lot of Micron memory arrived. Framework then:
  - refunded the difference on shipped orders automatically;
  - cut prices on pending pre-orders;
  - let customers switch back to larger memory;
  - paid return shipping.

  Pre-order prices are honoured when prices rise, and price cuts are applied automatically. Customers who edit an order move to current prices. [1]
- **Why it works for them:** Pre-orders mean Framework knows every affected customer. The amounts were limited.
- **Fit:** gap. The framework has no rule for what happens when costs fall. This is the strongest evidence so far that a pricing promise can hold in the direction that costs the company money.
- **Transfer:** commit in advance that cost decreases are passed on automatically, without the customer having to ask.

### FRM-04: Downgrading pre-orders instead of cancelling or charging more

- **What the company does:** In July 2026 the supplier quoted "more than double" for LPCAMM2 memory, against Framework's forecast of a "low-to-mid double digit" increase. Framework changed later 64GB orders to 32GB and later 32GB DIY orders to 16GB, at each smaller size's original price. It announced this publicly, explained the batch cut-offs, and partly reversed it in September. [1, 39]
- **Why it works for them:** Every order shipped, and nobody paid more than they agreed to.
- **Fit:** gap, and contested. Customers kept their price but got less than they ordered; CNET called it "a less conventional twist" [39]. The change was made for customers, not chosen by them.
- **Candidate to adapt:** keep the transparency, but give customers the choice: downgrade, wait, pay the difference or cancel. Don't decide for them.

### FRM-05: Weighted average cost, and pointing customers elsewhere

- **What the company does:** Memory is priced at the weighted average cost of inventory, so cheaper earlier stock lowers the price. The DIY Edition lets customers bring their own memory, storage and operating system. Framework recommends buying RAM elsewhere when that is cheaper and links to PCPartPicker from its own configurator. [1, 7]
- **Why it works for them:** Margins come from the laptop and parts ecosystem, not from memory upsell. Repairability makes third-party parts work.
- **Fit:** gap. This is a fairness practice like Buffer cancelling unused subscriptions (BUF-15) and Patagonia's "buy less, repair more" (PAT-05): the company points customers to the cheaper option even when it loses the sale.
- **Transfer:** name a cost basis for prices (average, replacement or historical cost) and say it.

### FRM-06: Publishing the loss calculation

- **What the company does:** In April 2025 Framework paused US sales of its cheapest models because of new tariffs and gave its reasoning in public: "At a 10% tariff, we would have to sell the lowest-end SKUs at a loss. Other consumer goods makers have performed the same calculations… though most have not been open about it." It reversed the price rises two days later, when the tariffs were paused. [2, 3]
- **Fit:** partial. This is cost disclosure in the framework's sense, used to explain why a product wasn't sold rather than to justify a price.
- **Transfer:** when a product is withdrawn or paused for cost reasons, publish the calculation.

### FRM-07: Repairability and upgradeability as the product

- **What the company does:**
  - Every Laptop 13 generation fits the original chassis.
  - New mainboards are sold as upgrades.
  - There is a first-party parts Marketplace.
  - Old boards can be reused in a case.
  - Refurbished and older stock goes to an Outlet.
  - iFixit scores 10/10.

  [7, 13, 30, 32]
- **Why it works for them:** It is the founding idea and the brand. The 2019 manifesto made the parts marketplace the way to earn money from openness [14].
- **Fit:** gap. The framework doesn't address product longevity. It supports FD-08 (impact) and FD-07 (long-term horizon: products designed to be kept, not replaced).
- **Transfer:** for physical or software products, commit to compatibility and a parts or upgrade path for a stated period.

### FRM-08: Open specifications, closed core

- **What the company does:** Expansion Card designs, embedded-controller firmware, mainboard documentation and keyboard firmware are on GitHub. The main BIOS stays proprietary (InsydeH2O). This is a frequent criticism, and firmware has been the company's weakest area. [13, 23, 31]
- **Fit:** partial. The framework says all aspects are public. Framework opens what lets others build and repair, but keeps closed the part that causes the most problems.
- **Transfer:** publish interfaces and specifications first. If something stays closed, say why.

### FRM-09: Open interfaces become community products

- **What the company does:** The open Expansion Card and Laptop 16 expansion-bay specifications let the community build modules. Community experiments led to the OCuLink Dev Kit [5]. A third party (DeepComputing) built a RISC-V mainboard for the Laptop 13 shell [13]. Top community requests ("AMD when?", "Upgradeable graphics when?", "Can I invest?") were all delivered [10].
- **Fit:** match. This is principle 2 in practice, and a different route from Buffer's upvote roadmap (BUF-08) or LEGO Ideas: the community builds, and the company adopts what works.
- **Transfer:** publish the interfaces that let users extend the product, then watch what they build.

### FRM-10: No public roadmap

- **What the company does:** Products are revealed at launch events: March 2023, February 2025, April 2026. There is no public roadmap, and forum users ask for one [47].
- **Why it works for them:** Hardware has long lead times, supplier confidentiality and launch-marketing effects. An early announcement can also stall sales of current models.
- **Fit:** differs from principle 4 (public task boards and roadmaps).
- **Candidate to adapt:** a public roadmap of *problems being worked on* (battery life, firmware, AMD support) without dates or product names. This keeps the community link without pre-announcing products.

### FRM-11: Admitting shortfalls, delays and incidents

- **What the company does:**
  - On firmware: "We recognize that we have fallen short of where we need to be on software updates" (2024).
  - Delays explained with causes: the Laptop 13 Pro touchpad circuit board and display firmware, with full refunds offered.
  - Both data incidents disclosed within hours, in 2024 and 2026.

  [13, 23, 28, 29, 38]
- **Fit:** match with principle 1. It is comparable to Buffer's post-mortems (BUF-13) and Toyota's hansei (TOY-15), though without published figures (for example, how many boards were bricked).

### FRM-12: Sponsorships published only after a controversy

- **What the company does:** In October 2025 Framework faced criticism for promoting Omarchy and sponsoring Hyprland. It then published its full sponsorship list, writing "This is certainly something we should have been doing already for transparency." It promised more community input on sponsorships and kept a "big tent" position: no partner choice based on politics. [15, 16, 17]
- **Fit:** partial. The disclosure was reactive, like Everlane's workforce data after 2020 (EVL-12). The "big tent" stance raises a question the framework doesn't answer: does community input extend to choosing partners and spending?
- **Transfer:** publish who you fund or partner with as standard practice, not after a dispute, and state the criteria.

### FRM-13: Warranty exceptions decided only after press coverage

- **What the company does:** In 2026, BIOS 3.20 left some Laptop 13 Ryzen 7040 boards unable to boot. Support first told some out-of-warranty owners to buy new boards. After coverage by Ars Technica and The Verge, Framework made exceptions "where we can confirm a stable-release BIOS update caused the board to become non-bootable" and promised a recovery-mode BIOS by year-end. [25, 26, 27]
- **Fit:** partial. The outcome was fair, but it was decided case by case, under pressure.
- **Candidate to adapt (FD-06):** a published rule in advance: faults the company causes are fixed regardless of warranty.

### FRM-14: Little venture money and a community round

- **What the company does:** About $45M from venture investors since 2021, led by Spark Capital. Patel: "raise as little as possible." In April 2024 a $1M community round let 100 accredited investors put in $10,000 each. [10, 11, 12, 13]
- **Fit:** gap (ownership is not in the framework). The community round is a small step towards community ownership. It was limited to accredited investors, so it excluded most of the community.
- **Transfer:** if outside money is taken, reserve a share for the community, through a structure open to non-accredited investors (crowdfunding or a cooperative share).

### FRM-15: Direct-to-consumer, financed by pre-orders

- **What the company does:** "It's all direct to consumer… we don't deal with distributors or channels or retail." Patel describes "a positive cash cycle": customers pay before suppliers are paid [11].
- **Fit:** gap. It is a financing model that reduces the need for outside capital (FD-01) and ties production to real demand (FD-07). The risk is that pre-orders turn customers into creditors, so delays and price changes fall on them, as with FRM-04.

### FRM-16: Honest environmental claims, thin supply-chain data

- **What the company does:** "We are not Sustainable. And neither is any other device maker." It reports recycled aluminium and packaging, and has a Fraunhofer IZM life-cycle analysis. No supplier list, conflict-minerals report, labour audit or take-back programme was found. [32]
- **Fit:** partial. The tone is the opposite of Everlane's marketing claims (EVL-02), but the substance is far behind Patagonia's supplier reporting (PAT-06, PAT-10).

### FRM-17: No financial disclosure

- **What the company does:** No revenue, profit, unit sales, headcount or cap table is published. The only financial signals are statements: "positive cash cycle" (2024) and "real financial risk" (2026). [1, 11]
- **Fit:** differs from principle 1, the same pattern as Patagonia (PAT-07). It is open about prices but closed about the business behind them.
- **Candidate for rejection:** the framework's minimum public set (FD-03) should include basic financials, especially when prices are justified by costs. Otherwise "only to cover costs" can't be checked from outside.

## 4. Where the framework goes further than this company

- **Public roadmaps and task boards (principle 4):** Framework has none (FRM-10). Buffer's roadmap (BUF-08) is the counter-example.
- **"All aspects transparent":** Framework keeps finances, firmware source and supplier data closed (FRM-08, FRM-16, FRM-17).
- **Full cost disclosure:** Framework discloses cost *changes* and per-unit component costs, not a full cost structure or margin.

## 5. Candidates for explicit rejection

- **FRM-17, closed finances:** reject for the framework, as with PAT-07. Prices justified by costs need numbers behind them.
- **FRM-10, roadmap only at launch events:** reject in its pure form; adapt as a public list of problems being worked on.
- **FRM-04, unilateral downgrades:** adapt, so customers choose.

## 6. Open questions for the decisions

- **FD-04:** is a published pricing rule (FRM-01) plus a change log (FRM-02) a better requirement than a full cost breakdown? Or should both be required? Everlane shows that a breakdown alone can become marketing; Framework shows that a rule plus a log can be checked.
- **FD-05:** does community-driven development need a roadmap, or can open interfaces (FRM-09) do the same job?
- **FD-03 and FD-06:** should the framework require rules decided in advance for the situations that most often go wrong: price changes, faults the company causes, partner choices?
- **FD-01:** can community investment be opened to non-accredited investors where the law allows?

## 7. Updates

- 2026-11-23: comparison written.

## Sources

Source list from the underlying company study. Numbering matches the brackets above.

| # | Author / outlet | Title | Date | Type | Link |
|---|---|---|---|---|---|
| 1 | Nirav Patel, Framework blog | Navigating the volatile silicon market: updates on memory and storage pricing | Dec 2025 – Nov 6 2026 (updated in place) | primary | https://frame.work/blog/updates-on-memory-pricing-and-navigating-the-volatile-memory-market |
| 2 | Framework (forum mirror of blog) | Tariff-driven price and availability changes for US customers | Apr 2025 | primary | https://community.frame.work/t/tariff-driven-price-and-availability-changes-for-us-customers/67307 |
| 3 | Mark Hachman, PCWorld | Framework 'pauses' some laptop sales in response to tariffs | Apr 2025 | press | https://www.pcworld.com/article/2660679/framework-pauses-some-laptop-sales-in-response-to-tariffs.html |
| 4 | Laptop Mag | Framework built one of the last laptops you'll ever need to buy — but it can't sell it to you | Apr 2025 | press | https://www.laptopmag.com/au/laptops/framework-built-one-of-the-last-laptops-youll-ever-need-to-buy-but-it-cant-sell-it-to-you |
| 5 | Framework | Framework Laptop 13 Pro and highlights from the Framework [Next Gen] Event | 2026-04-21 | primary | https://community.frame.work/t/framework-laptop-13-pro-and-highlights-from-the-framework-next-gen-event/81954 |
| 6 | Framework | Framework Laptop 13 Pro press reviews and previewing a 192GB Framework Desktop | ~2026-07-27 | primary | https://community.frame.work/t/framework-laptop-13-pro-press-reviews-and-previewing-a-192gb-framework-desktop/83707 |
| 7 | Framework | About | accessed 2026-11-23 | primary | https://frame.work/about |
| 8 | Framework blog | Reviews of the new Framework Laptop 12 are live | 2026-10-13 | primary | https://frame.work/blog/reviews-of-the-new-framework-laptop-12-are-live |
| 9 | Framework blog | Pre-orders open for Framework Wireless Touchpad Keyboard | 2026-11-17 | primary | https://frame.work/blog/pre-orders-open-for-framework-wireless-touchpad-keyboard |
| 10 | Framework | Framework's Series A-1 and Community Participation | 2024-04-23 | primary | https://community.frame.work/t/framework-s-series-a-1-and-community-participation/49523 |
| 11 | TechCrunch | Framework's repairability philosophy is set to expand beyond the laptop | 2024-04-23 | press | https://techcrunch.com/2024/04/23/frameworks-repairability-philosophy-is-set-to-expand-beyond-the-laptop |
| 12 | Nick Flaherty, eeNews Europe | Framework raises $18m to move beyond modular laptop | 2024-04-23 | press | https://www.eenewseurope.com/en/framework-raises-18m-to-move-beyond-modular-laptop |
| 13 | Wikipedia | Framework Computer | accessed 2026-11 | tertiary | https://en.wikipedia.org/wiki/Framework_Computer |
| 14 | Nirav Patel | Five years of Framework (includes 2019 manifesto) | early 2025 | primary | https://community.frame.work/t/five-years-of-framework/63010 |
| 15 | Nirav Patel, forum | Reply and Oct 14 2025 update in "Framework supporting far-right racists?" | Oct 2025 | primary | https://community.frame.work/t/framework-supporting-far-right-racists/75986/2 |
| 16 | Thomas Claburn, The Register | Framework flame war erupts over support of politically polarizing Linux projects | 2025-10-14 | press | https://www.theregister.com/software/2025/10/14/framework-flame-war-erupts-over-linux-controversy/1466815 |
| 17 | Framework blog | Framework sponsorships | 2025-10-14, updated 2025-12-03 and 2026-03-25 | primary | https://frame.work/blog/framework-sponsorships |
| 18 | It's FOSS | Framework is Accused of Supporting the Far-right… | 2025-10-13 | press | https://itsfoss.com/news/framework-hyprland-sponsorship |
| 19 | Sosthène Guédon | Why people are mad at Framework | 2025-10-26 | opinion | https://sgued.fr/blog/framework-omarchy |
| 20 | Framework forum | Why discord is kill? | Nov 2025 | community | https://community.frame.work/t/why-discord-is-kill/78021 |
| 21 | Arya | Framework under fire for Omarchy/DHH/Hyprland support? | 2025-10-10 | opinion | https://crimier.github.io/posts/Framework-Omarchy |
| 22 | scy | Why not Framework Computer? | 2026 | opinion | https://scy.name/why-not/framework.html |
| 23 | Andrew Cunningham, Ars Technica | Framework's software and firmware have been a mess, but it's working on them | 2024-04-15 | press | https://arstechnica.com/gadgets/2024/04/frameworks-software-and-firmware-have-been-a-mess-but-its-working-on-them |
| 24 | Andrew Cunningham, Ars Technica | Looking at Framework's progress on software support for its repairable laptops | 2025-06-25 | press | https://arstechnica.com/gadgets/2025/06/looking-at-frameworks-progress-on-software-support-for-its-repairable-laptops |
| 25 | Ars Technica | Framework responds to complaints that BIOS update bricks Ryzen 7040 laptops | 2026-08-19 | press | https://arstechnica.com/gadgets/2026/08/framework-responds-to-complaints-that-bios-update-bricked-ryzen-7040-laptops |
| 26 | The Verge | Framework says it's addressing a BIOS update that bricked some of its older laptops | 2026-08-20 | press | https://www.theverge.com/gadgets/982800/framework-laptop-13-amd-7040-bios-320-bricking-warranty |
| 27 | igor'sLAB (also BigGo Finance) | Framework confirms BIOS issues… | 2026-08-22 | press (secondary) | https://www.igorslab.de/en/framework-confirms-bios-issues-laptop-13-ryzen-7040-motherboards-fail-after-update-3-20 |
| 28 | TechCrunch | Framework says hackers accessed customer data after phishing attack on accounting partner | 2024-01-12 | press | https://techcrunch.com/2024/01/12/framework-customer-data-stolen-phishing-keating-accounting |
| 29 | Lorenzo Franceschi-Bicchierai, TechCrunch | Computer maker Framework notifies 'all customers' of a data breach | 2026-08-07 | press | https://techcrunch.com/2026/08/07/computer-maker-framework-notifies-all-customers-of-a-data-breach |
| 30 | iFixit | a) Framework Laptop teardown 10/10 (Sep 2021); b) Laptop 13 Pro device page; c) early Desktop teardown (2025-02-26) | 2021–2026 | press | https://www.ifixit.com/Teardown/Framework+Laptop+Teardown/145124 ; https://www.ifixit.com/Device/Framework_Laptop_13_Pro ; https://www.ifixit.com/News/108396/framework-let-us-in-for-an-early-teardown-of-the-refreshingly-open-framework-desktop |
| 31 | Framework | GitHub organisation | accessed 2026-11-23 | primary | https://github.com/FrameworkComputer |
| 32 | Framework | Sustainability | accessed 2026-11-23 | primary | https://frame.work/sustainability |
| 33 | Fieldfisher | Incoming EU right to repair requirements | 2026-07-06 | press (law firm) | https://www.fieldfisher.com/en/insights/incoming-eu-right-to-repair-requirements-the-key-t |
| 34 | European Commission | Commission adds exemptions to portable battery removal rules | 2026-07-14 | primary (regulator) | https://environment.ec.europa.eu/news/commission-adds-exemptions-portable-battery-removal-rules-2026-07-14_en |
| 35 | Adherent | Early signals from the EU's preparatory work for future ESPR delegated acts | 2026-06-29 | press (law firm) | https://www.adherent.com/blog/early-signals-from-the-eus-preparatory-work-for-future-espr-delegated-acts-on-electronics-textiles-and-iron-steel |
| 36 | PCMag | Framework: Our Linux Laptop 13 Pro Is Outselling the Windows Model | 2026-04-23 | press | https://www.pcmag.com/news/framework-our-linux-laptop-13-pro-is-outselling-the-windows-model |
| 37 | PCMag | Hands-on with the Framework Laptop 13 Pro | 2026-04-21 | press | https://www.pcmag.com/news/i-want-it-hands-on-with-the-framework-laptop-13-pro-a-new-premium-player |
| 38 | The Verge | Framework Laptop 13 Pro delay | 2026-06-10 | press | https://www.theverge.com/gadgets/948044/framework-laptop-13-pro-delay-shipment-july-august |
| 39 | CNET | Framework Passes Rising Memory and Processor Costs to Buyers, With a Twist | 2026-07-24 | press | https://www.cnet.com/tech/computing/framework-rising-laptop-prices-preorder-configuration-ram-memory |
| 40 | Tom's Hardware; Notebookcheck | a) Desktop price rise (2026-01-13); b) monthly memory update (2026-02-13); c) Notebookcheck on the Dec 2025 update | 2025–2026 | press | https://www.tomshardware.com/desktops/gaming-pcs/diy-pc-maker-framework-finally-succumbs-to-ram-apocalypse-is-raising-prices-on-its-desktops-now-starts-at-usd1-139-with-32gb-128gb-up-usd450 ; https://www.tomshardware.com/laptops/framework-releases-monthly-update-about-memory-and-storage-pricing-woes-ram-costs-increased-to-usd12-to-usd16-per-gb-recommends-purchasing-some-models-elsewhere-for-framework-laptop-diy-edition-customers ; https://www.notebookcheck.net/Framework-warns-of-further-laptop-price-increases-as-DDR5-RAM-costs-surge-while-announcing-a-further-price-adjustment-a-week-after-its-last-hike.1192510.0.html |
| 41 | PC Gamer | Framework raises its memory prices by 50 percent | ~2025-12-12 | press | https://www.pcgamer.com/hardware/memory/framework-raises-its-memory-prices-by-50-percent-but-says-it-is-highly-likely-that-we-will-need-to-make-further-price-updates-whether-ddr5-lpddr5x-or-gddr |
| 42 | Andrew Cunningham, Ars Technica | Framework Laptop 13 Pro review: Much better battery, much worse price | 2026-07-27 | press (headline only read) | https://arstechnica.com/gadgets/2026/07/framework-laptop-13-pro-review-much-better-battery-much-worse-price |
| 43 | Phoronix | Framework Desktop With AMD Ryzen AI Max+ PRO 495 Starts Out At $6799 USD | 2026-09-30 | press (headline only read) | https://www.phoronix.com/news/Framework-Desktop-Gorgon-Halo |
| 44 | Nirav Patel | LinkedIn; personal site | accessed 2026-11 | primary | https://eclecti.cc/about-me |
| 45 | Framework YouTube | Live Q&A with Framework Founder & CEO Nirav Patel | undated | primary | https://www.youtube.com/watch?v=JJRdUelpO7M |
| 46 | Trustpilot; Reddit r/framework | Customer reviews and support threads | Nov 2026 | community | https://www.trustpilot.com/review/frame.work |
| 47 | Framework forum | Please give us a future roadmap | 2025/2026 | community | https://community.frame.work/t/please-give-us-a-future-roadmap/77756 |
| 48 | YesPress | Framework: The Laptop Built to Be Repaired… | 2026-08-19 | press (unsourced figures) | https://yespress.io/framework |
| 49 | Gizmodo | Framework Laptop 13 Pro Review | 2026-07-28 | press | https://gizmodo.com/framework-laptop-13-pro-review-the-best-modular-laptop-ever-made-2000791804 |
