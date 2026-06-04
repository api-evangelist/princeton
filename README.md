# Princeton University (princeton)

Princeton University is a private Ivy League research university in Princeton, New Jersey, ranked #13 in the QS World University Rankings 2025. This repository catalogs Princeton's public developer and API footprint as an [APIs.json](https://apisjson.org) provider profile. The most openly accessible API is the Princeton University Art Museum collections API; most institutional APIs are gated behind NetID/service-account authentication.

- APIs.json: https://raw.githubusercontent.com/api-evangelist/princeton/refs/heads/main/apis.yml
- Run with Naftiko: https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=princeton-api-evangelist&utm_content=repo

## Type

- Index / Consumer / 3rd-Party

## Tags

Education, Higher Education, University, Ivy League, United States, Open Data, Museum, Library

## APIs

- **Princeton University Art Museum API** — Open, no-auth REST API for collections data (objects, makers, packages, search) with IIIF imagery. Docs: https://github.com/Princeton-University-Art-Museum/puam-api-docs
- **Princeton OIT API Store** — OAuth2-gated gateway exposing ActiveDirectory, PrincetonInfo, and MobileApp (courses/dining/places) APIs to the campus community. Docs: https://api-store.princeton.edu/store/
- **DataSpace OAI-PMH** — DSpace digital repository metadata-harvesting endpoint (auth required). Docs: https://dataspace.princeton.edu/about

## Plans

- [plans/princeton-plans-pricing.yml](plans/princeton-plans-pricing.yml)

## Rate Limits

- [rate-limits/princeton-rate-limits.yml](rate-limits/princeton-rate-limits.yml)

## FinOps

- [finops/princeton-finops.yml](finops/princeton-finops.yml)

## Timestamps

- Created: 2026-06-03
- Modified: 2026-06-03

## Common Properties

- Website: https://www.princeton.edu/
- GitHub: https://github.com/pulibrary
- LinkedIn: https://www.linkedin.com/school/princeton-university/
- Developer Portal: https://api-store.princeton.edu/store/
- Source Code: https://github.com/Princeton-University-Art-Museum
- Review: [review.yml](review.yml)

## Notes

All entries reflect URLs probed on 2026-06-03. The Art Museum API responded live (HTTP 200, no auth). The OIT API Store was not reachable from the public internet (connection refused) and is gated behind campus/OAuth2 access. The DataSpace OAI-PMH endpoint exists but returned HTTP 401 (auth required). Princeton Data Commons (datacommons.princeton.edu) is the newer research data repository succeeding DataSpace. No endpoints were fabricated.

## Maintainers

- Kin Lane — kin@apievangelist.com
