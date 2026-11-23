# Research behind the framework

The framework is built from comparative studies of companies. This folder holds what the studies taught: each company's practices compared with the framework, a cross-company practice index, and the decision log that turns evidence into framework text.

**The question:** *what makes a good company with a real customer and product focus, and what keeps it that way?* The framework is a hypothesis tested against that question. A practice that differs from the framework can be the better answer.

## How it fits together

1. **Company research** (kept outside this repo): history, current state and outlook of each company, from sourced reporting. New events at a company are tracked as news and measured against the framework.
2. **Comparison** (`comparisons/<company>.md`): the company's practices one by one (`TOY-01`, …), each compared with the framework, with the sources at the end.
3. **Practice index** (`practices.md`): every practice from every company in one list, sorted by area, so practices on the same question can be compared side by side.
4. **Decision log** (`decisions.md`): the questions the framework has to answer (`FD-01`, …). Each topic collects the practices that bear on it and records the outcome per practice: adopt, adapt, reject or park. Rejections are listed explicitly, with why and what the framework does instead.
5. **Framework**: the decided text goes into the main [README](../README.md); changes are logged in [CHANGELOG.md](../CHANGELOG.md).

New evidence (a new company, or a new event at a studied company) adds practices and evidence to open topics, or reopens a decided one with a new topic. It never changes a decision by itself.

## Companies

| ID | Company | Prefix | Category | Comparison |
|---|---|---|---|---|
| CS-001 | Toyota | TOY | model / mixed | [comparisons/toyota.md](comparisons/toyota.md) |
| CS-002 | Buffer | BUF | model | [comparisons/buffer.md](comparisons/buffer.md) |
| CS-003 | GitLab | GIT | cautionary / mixed | [comparisons/gitlab.md](comparisons/gitlab.md) |
| CS-004 | Framework Computer | FRM | model | [comparisons/framework-computer.md](comparisons/framework-computer.md) |
| CS-005 | LEGO | LEG | model | [comparisons/lego.md](comparisons/lego.md) |
| CS-006 | Costco | COS | model | [comparisons/costco.md](comparisons/costco.md) |
| CS-007 | Starbucks | SBX | turnaround | [comparisons/starbucks.md](comparisons/starbucks.md) |
| CS-008 | Boeing | BOE | turnaround | [comparisons/boeing.md](comparisons/boeing.md) |
| CS-009 | Southwest Airlines | SWA | cautionary | [comparisons/southwest.md](comparisons/southwest.md) |
| CS-010 | Everlane | EVL | cautionary | [comparisons/everlane.md](comparisons/everlane.md) |
| CS-011 | Nike | NKE | turnaround | [comparisons/nike.md](comparisons/nike.md) |
| CS-012 | Patagonia | PAT | model | [comparisons/patagonia.md](comparisons/patagonia.md) |
| CS-013 | Haier | HAI | model | [comparisons/haier.md](comparisons/haier.md) |
| CS-014 | Ben & Jerry's | BNJ | cautionary | [comparisons/ben-and-jerrys.md](comparisons/ben-and-jerrys.md) |
| CS-015 | Fairphone | FAI | model | [comparisons/fairphone.md](comparisons/fairphone.md) |

Category: `model` (does parts of the framework well) · `turnaround` (lost its way, trying to recover) · `cautionary` (gave its values up, or is drifting) · `mixed`.

IDs and prefixes are never reused.

## Area codes

Every practice gets one or two areas. They date from the original draft framework and are kept so older entries stay readable.

| Code | Area |
|---|---|
| TR | Transparency and accountability |
| PD | Product development and customer insight |
| PR | Pricing |
| PM | Project management and decision-making |
| CI | Continuous improvement |
| CO | Communication, documentation and customer relationship |
| PE | Employees |
| SU | Suppliers and partners |
| EN | Environment and supply-chain impact |
| OW | Ownership and capital |
| LT | Long-term horizon and growth |

## Fit values

- `match`: the framework already says this
- `partial`: same goal, different method or a different audience
- `gap`: the company does something the framework doesn't address
- `differs`: the company does the opposite of what the framework says

Fit describes the relationship to the framework version a comparison used (its *Framework version compared* field). Comparisons written before 2026-11-23 use the original draft and its numbering. Fit is **not a verdict**: whether a practice is good is judged against the question above, in `decisions.md`.

## Signals and outcomes

- **Signal** (a first read, not a decision): `adopt?` · `adapt?` · `reject?` · `park?` · `recheck?` · blank
- **Outcome**: `to decide` · `adopt` (take it as is) · `adapt` (take the idea, change the method) · `reject` (decide against it, even though it works elsewhere) · `park` (not now) · `note only`
- **Topic status**: `open` · `decided YYYY-MM-DD` · `superseded by FD-xx`

## Rules

- Only the maintainer decides a topic. Research may add practices, evidence, options and recommendations, and open new topics, but never fills in a decision.
- **What, not how:** the framework states what a company commits to. Methods, examples and evidence stay in this folder unless the method itself is key.
- Before adopting a practice, check the conditions that make it work for that company (size, industry, ownership, customers).
- Facts, claims and analysis are kept apart, and every fact has a source.
