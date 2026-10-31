# Princeton University

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Princeton University is a private Ivy League research university in Princeton, New Jersey. Its programmable footprint is real but almost entirely the work of one unit — Princeton University Library — and it is one of the few institutions in this cohort that operates its own machine-readable contract rather than a vendor's. The Library publishes an OpenAPI 3.1.1 document for its Allsearch API at allsearch-api.princeton.edu, serves a Swagger UI alongside it, open-sources the application behind it, and runs a family of unauthenticated Blacklight JSON endpoints across the catalog, digital collections, finding aids, maps and the Princeton Data Commons research-data portal. The Art Museum runs a separate open, no-authentication collections API documented in prose on GitHub. Princeton also operates its own Shibboleth identity provider with published SAML 2.0 metadata, an OAI-PMH 2.0 endpoint on Figgy, and DataCite DOI registration under three of its own repository clients. Everything outside the Library is gated: the OIT enterprise gateway at api.princeton.edu runs WSO2 API Manager behind NetID or service-account OAuth2, and the developer portal that used to front it, api-store.princeton.edu, no longer resolves at all. Course, registrar, dining and directory data exist as APIs but are not reachable by anyone without a Princeton credential, so no public course-catalog surface is claimed here. Princeton's teaching and library-discovery layers are vendor tenancies — Canvas and Ex Libris Alma/Primo — and are recorded as relationships, not as Princeton contracts.

**Areas:** University · Higher Education · Education · Ivy League · United States · New Jersey · Research Library · Research Data · Open Data · Digital Collections · Identity Federation · Museums

## Princeton University on APIs.io

Everything profiled for Princeton University is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/princeton/](https://apis.io/providers/princeton/)** — or go straight to one of the APIs or properties below.

### APIs (30)

- [Princeton University Art Museum API](https://apis.io/apis/princeton/art-museum-api/) — Open, REST-style API providing developer access to data about the Princeton University Art Museum and its collections. Four surfaces: objects (with a…
- [Princeton OIT API Gateway](https://apis.io/apis/princeton/oit-api-gateway/) — Princeton's Office of Information Technology enterprise API gateway, running WSO2 API Manager. Fronts institutional APIs — ActiveDirectory user and group…
- [Princeton University Library Catalog (Orangelight)](https://apis.io/apis/princeton/catalog/) — Princeton's library catalog at catalog.princeton.edu, a Blacklight application the Library writes and maintains itself as pulibrary/orangelight. Every route…
- [PUL Bibliographic Data Web Service (Bibdata)](https://apis.io/apis/princeton/bibdata/) — Princeton University Library's own bibliographic data service at bibdata.princeton.edu. A Rails application (pulibrary/bibdata) that reads from Alma and…
- [Figgy Digital Repository — OAI-PMH and IIIF](https://apis.io/apis/princeton/figgy-oai/) — Figgy is Princeton University Library's Valkyrie-based digital repository backend (pulibrary/figgy). It serves IIIF manifests for digitised material and…
- [Princeton Data Commons — Discovery](https://apis.io/apis/princeton/data-commons/) — Princeton's research data repository, split into pdc_describe for deposit and description and pdc_discovery for the public portal at…
- [DataSpace Institutional Repository — OAI-PMH](https://apis.io/apis/princeton/dataspace-oai/) — DataSpace is Princeton's older DSpace-based institutional repository for theses, dissertations and archived research output, with an OAI-PMH…
- [Princeton University Library Finding Aids (PULFAlight)](https://apis.io/apis/princeton/finding-aids/) — Archival finding aids for Princeton's special collections and the Mudd Manuscript Library, served by an ArcLight application the Library maintains as…
- [Princeton University Library Maps and Geospatial Data (PUL Map)](https://apis.io/apis/princeton/maps/) — GeoBlacklight application at maps.princeton.edu (pulibrary/pulmap) serving Princeton's geospatial data catalog. The .json surface is anonymously readable…
- [Digital PUL (DPUL)](https://apis.io/apis/princeton/digital-pul/) — Princeton's public digital collections site at dpul.princeton.edu (pulibrary/dpul), the presentation layer over Figgy. Blacklight .json endpoints return…
- [Princeton Shibboleth Identity Provider — SAML 2.0 Metadata](https://apis.io/apis/princeton/shibboleth-idp/) — Princeton's campus identity provider publishes signed SAML 2.0 metadata at idp.princeton.edu/idp/shibboleth. The EntityDescriptor names Princeton…
- [Ex Libris Alma / Primo VE — Princeton tenancy (01PRI_INST)](https://apis.io/apis/princeton/exlibris-tenancy/) — Princeton's library management and discovery layer runs on Ex Libris, with institution code 01PRI_INST: Alma at na05.alma.exlibrisgroup.com and a Primo VE…
- [Canvas LMS — Princeton tenancy](https://apis.io/apis/princeton/canvas-tenancy/) — Princeton's learning management system is Instructure Canvas at princeton.instructure.com. The host is live behind a Cloudflare interstitial (403 to…
- [Princeton University Article API](https://apis.io/apis/princeton/princeton-article-api/) — The Article API from Princeton University — 1 operation(s) for article.
- [Princeton University Banner API](https://apis.io/apis/princeton/princeton-banner-api/) — The Banner API from Princeton University — 1 operation(s) for banner.
- [Princeton University Best Bets API](https://apis.io/apis/princeton/princeton-best-bets-api/) — The Best Bets API from Princeton University — 1 operation(s) for best bets.
- [Princeton University Catalog API](https://apis.io/apis/princeton/princeton-catalog-api/) — The Catalog API from Princeton University — 1 operation(s) for catalog.
- [Princeton University Dpul API](https://apis.io/apis/princeton/princeton-dpul-api/) — The Dpul API from Princeton University — 1 operation(s) for dpul.
- [Princeton University Findingaids API](https://apis.io/apis/princeton/princeton-findingaids-api/) — The Findingaids API from Princeton University — 1 operation(s) for findingaids.
- [Princeton University Journals API](https://apis.io/apis/princeton/princeton-journals-api/) — The Journals API from Princeton University — 1 operation(s) for journals.
- [Princeton University Libanswers API](https://apis.io/apis/princeton/princeton-libanswers-api/) — The Libanswers API from Princeton University — 1 operation(s) for libanswers.
- [Princeton University Libguides API](https://apis.io/apis/princeton/princeton-libguides-api/) — The Libguides API from Princeton University — 1 operation(s) for libguides.
- [Princeton University Library Databases API](https://apis.io/apis/princeton/princeton-library-databases-api/) — The Library Databases API from Princeton University — 1 operation(s) for library databases.
- [Princeton University Library Staff API](https://apis.io/apis/princeton/princeton-library-staff-api/) — The Library Staff API from Princeton University — 1 operation(s) for library staff.
- [Princeton University Library Website API](https://apis.io/apis/princeton/princeton-library-website-api/) — The Library Website API from Princeton University — 1 operation(s) for library website.
- [Princeton University Makers API](https://apis.io/apis/princeton/princeton-makers-api/) — Artists, cultural groups and other makers.
- [Princeton University Objects API](https://apis.io/apis/princeton/princeton-objects-api/) — Art objects in the Museum's collection.
- [Princeton University Packages API](https://apis.io/apis/princeton/princeton-packages-api/) — Curated groupings of collection material.
- [Princeton University Pulmap API](https://apis.io/apis/princeton/princeton-pulmap-api/) — The Pulmap API from Princeton University — 1 operation(s) for pulmap.
- [Princeton University Search API](https://apis.io/apis/princeton/princeton-search-api/) — Full-text search across all collection data types.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### JSON Schema (3)

The data models the API reads and writes.

- [Princeton Allsearch error envelope](https://apis.io/schemas/princeton/princeton-allsearch-error/)
- [Princeton Allsearch search response](https://apis.io/schemas/princeton/princeton-allsearch-search-response/)
- [Princeton University Art Museum art object](https://apis.io/schemas/princeton/princeton-art-museum-object/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Princeton Context](https://apis.io/jsonld/princeton/princeton-context/)

#### Examples (5)

Example requests and responses.

- [Princeton Allsearch Banner 200](https://apis.io/examples/princeton/princeton-allsearch-banner-200/)
- [Princeton Allsearch Catalog Search 200](https://apis.io/examples/princeton/princeton-allsearch-catalog-search-200/)
- [Princeton Allsearch Empty Query 400](https://apis.io/examples/princeton/princeton-allsearch-empty-query-400/)
- [Princeton Art Museum Maker 200](https://apis.io/examples/princeton/princeton-art-museum-maker-200/)
- [Princeton Art Museum Tombstone 200](https://apis.io/examples/princeton/princeton-art-museum-tombstone-200/)

#### Governance rules (1)

Spectral rulesets for the provider's contracts.

- [Princeton University — openapi rules](https://apis.io/rules/princeton/princeton-openapi-spectral-rules/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [Princeton Authentication](https://apis.io/security/princeton/princeton-authentication/)
- [Princeton Domain Security](https://apis.io/security/princeton/princeton-domain-security/)

#### OAuth scopes (1)

The permissions the API asks for.

- [Princeton Scopes](https://apis.io/scopes/princeton/princeton-scopes/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Princeton Plans Pricing](https://apis.io/plans/princeton/princeton-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Princeton Rate Limits](https://apis.io/rate-limits/princeton/princeton-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Princeton Finops](https://apis.io/finops/princeton/princeton-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.princeton.edu/)
- [API reference](https://allsearch-api.princeton.edu/api-docs)
- [Blog](https://www.princeton.edu/news)
- [Privacy policy](https://www.princeton.edu/privacy-notice)
- [GitHub](https://github.com/pulibrary)

## API Evangelist rating

**Kin Score 33.5** — thin · rubric 0.24.0 · scored 2026-10-17

| Facet | Score |
|---|---|
| Discoverability | 53.6 |
| Contract quality | 49.6 |
| Contract governance | 29.5 |
| Operational transparency | 7.9 |
| Developer ergonomics | 31.0 |
| Access clarity | 15.8 |

**Agent readiness 27.8** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | — |
| Reversibility Documented | na |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | na |
| Error Semantics | documented (partial credit) |
| OpenAPI Examples | verified |
| Rate Limit Signal | derived (partial credit) |
| Event Surface Described | — |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | na |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |

**Regulatory alignment 30.4** — Education & Research

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/princeton/](https://apis.io/providers/princeton/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Princeton University: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/princeton/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
