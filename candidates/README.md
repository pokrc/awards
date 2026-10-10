# Public candidates

The [register below](#candidate-register) is the public notice table, maintained
by administrators after any required participant PR merges. Each contribution type's
14-day review starts when its candidate is added for public notice, once the
mathematical solution and Lean proof have passed review and verification.

Follow the [award process](../docs/award-process.md#the-14-day-public-review) for
publication, challenges, replacements and review completion. Solver applications
awaiting formalization remain in their claim issue or submission PR without an
active review clock. Both claim statuses remain **Unavailable** unless the
problem bank's shared **Eligible to claim** flag is **Yes**, requiring both a
mathematical solution and a Lean proof. Once eligible, mark each role **Unclaimed**
until its candidate is published here, then **Claimed**. Opening a claim issue
alone does not mark a role **Claimed**. These statuses do not announce awards.

## Candidate register

The two review-start columns record when each contribution type's public notice
began, using UTC. Existing date-only entries retain their recorded publication
dates; no time of day is inferred from a PR merge. Empty cells mean that no candidate for that role is
published in this register. They do not mean the problem lacks a mathematical
solution or Lean formalization. Problem IDs link to the problem bank for public
contribution attribution and evidence. Publication is not an award or recipient
identity confirmation; identity checks and written confirmation remain required.

| Problem ID | Solver review start (UTC) | Mathematical solver | Lean review start (UTC) | Lean formalizer |
| --- | --- | --- | --- | --- |
| [JSP-000239](../problems/catalog-0201-0300.md#JSP-000239) | 2026-09-30 | Neel Somani | | |
| [JSP-000327](../problems/catalog-0301-0400.md#JSP-000327) | 2026-09-30 | Neel Somani | | |

Contributions whose public-review period ran from 2026-09-19 to 2026-10-03
have moved to the [award register](../awards/README.md#award-register).

When a role is awarded, replace its active candidate cell with a labeled link to
the award record and retain its completed review dates in that record. The other
role keeps its own clock. Keep the awarded role's claim status **Claimed** in
the problem index, including after its candidate entry is removed.
Remove a problem row once neither role remains a
candidate. If a contribution is invalidated without an accepted replacement,
remove its active candidate and review dates and retain the history. If no valid
formalization remains, retain the solver application without an active clock.
Detailed identity checks, payment/delivery information and correspondence stay
out of this public register.
