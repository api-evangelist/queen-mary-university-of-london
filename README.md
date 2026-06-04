# Queen Mary University of London (queen-mary-university-of-london)

Queen Mary University of London (QMUL) is a public research university and Russell Group member in London, United Kingdom, ranked #120 in the QS World University Rankings 2025. This repository catalogs QMUL's public, machine-accessible developer/API footprint as an [APIs.json](https://apisjson.org) provider profile for the API Evangelist network. QMUL has no central branded developer portal; its confirmed public surface is research- and library-oriented (an open-access DSpace repository with OAI-PMH, plus a staff GitHub organization).

- APIs.json: https://raw.githubusercontent.com/api-evangelist/queen-mary-university-of-london/refs/heads/main/apis.yml
- Run with Naftiko: https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=queen-mary-university-of-london-api-evangelist&utm_content=repo

## Type

- Index / Consumer / 3rd-Party

## Tags

Education, Higher Education, University, Research, Open Access, Repository, OAI-PMH, Library, United Kingdom, London

## APIs

- **Queen Mary Research Online (QMRO) OAI-PMH Interface** — Public OAI-PMH 2.0 metadata-harvesting endpoint over the QMRO DSpace open-access institutional repository. No authentication required.
  - Docs: https://qmro.qmul.ac.uk/
  - Base URL: https://qmro.qmul.ac.uk/oai/request
  - OpenDOAR record: https://opendoar.ac.uk/repository/2185
- **QMUL GitHub Organization** — Public open-source code released by QMUL staff (research and teaching repositories). Source code, not a hosted API product.
  - Docs: https://github.com/QMUL

## Plans

- [plans/queen-mary-university-of-london-plans-pricing.yml](plans/queen-mary-university-of-london-plans-pricing.yml)

## Rate Limits

- [rate-limits/queen-mary-university-of-london-rate-limits.yml](rate-limits/queen-mary-university-of-london-rate-limits.yml)

## FinOps

- [finops/queen-mary-university-of-london-finops.yml](finops/queen-mary-university-of-london-finops.yml)

## Timestamps

- Created: 2026-06-03
- Modified: 2026-06-03

## Common Properties

- Website: https://www.qmul.ac.uk/
- GitHub: https://github.com/QMUL
- LinkedIn: https://www.linkedin.com/school/queen-mary-university-of-london
- Repository: https://qmro.qmul.ac.uk/
- Plans, RateLimits, FinOps, Review pointers (see files above and [review.yml](review.yml))

## Notes

- No public, signup-gated REST API program or central developer portal was found for QMUL as of the review date.
- The QMRO OAI-PMH endpoint (`verb=Identify`) returned HTTP 200, but the host intermittently rate-limits non-browser clients; corroborated as a DSpace repository by OpenDOAR/ROAR.
- The main website, MyQMUL portal, and FOI datasets page return HTTP 403 to scripted requests (browser/auth oriented). QMplus (Moodle) loads publicly but is a gated LMS, not a documented API.
- No endpoints were fabricated; only URLs probed live or independently corroborated are cataloged.

## Maintainers

- Kin Lane — kin@apievangelist.com
