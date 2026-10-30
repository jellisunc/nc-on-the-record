# NC On The Record

A nonpartisan record check for North Carolina's unaffiliated voters, built for the
November 3, 2026 general election.

**Format:** "Says vs. Did" — each candidate's stated positions (their own words,
sourced to their campaign) next to their actual record (vetoes, votes, rulings,
official filings), plus a factual risk check and labeled contested claims.
Same structure and rules for every candidate, regardless of party.

**Coverage (v1, focused):**
- U.S. Senate (open seat): Roy Cooper (D), Michael Whatley (R), Shannon Bray (L), Michael Dublin (G)
- NC Supreme Court: Anita Earls (D) vs Sarah Stevens (R)
- The 3 statewide constitutional amendments, in plain English
- Voting logistics for unaffiliated voters + official NCSBE ballot lookup

**Stack:** single static `index.html`, no build step. Deploy as a static site
(Render: publish directory = repo root).

**Research dossiers** (the sourced material the page is built from) live in
`research/`. Every claim on the page traces to a source in those files.
