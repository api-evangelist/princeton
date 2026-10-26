# Princeton University (princeton)

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

Princeton University is a private Ivy League research university in Princeton, New Jersey. This
repository catalogs Princeton's public developer and API footprint as an
[APIs.json](https://apisjson.org) provider profile, re-profiled on 2026-08-19 under the API
Evangelist **university pipeline**, which settles WHO OPERATES each surface before saving anything.

Princeton is one of the few institutions in this cohort that publishes a machine-readable contract
of its own rather than a vendor's. Almost all of it is the work of Princeton University Library.

- APIs.json: https://raw.githubusercontent.com/api-evangelist/princeton/refs/heads/main/apis.yml
- Run with Naftiko: https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=princeton-api-evangelist&utm_content=repo

## Type

- University / Private Research University / Provider

## Tags

University, Higher Education, Education, Ivy League, United States, New Jersey, Research Library,
Research Data, Open Data, Digital Collections, Identity Federation, Museum

## Surfaces, by operator

Every surface carries an `x-operator`: `institution` means Princeton runs the thing the contract
describes; `tenant` means Princeton's data on a vendor's platform, where the contract belongs to the
vendor and is scored against the vendor.

### institution (12)

- **Princeton University Library Allsearch API** — `allsearch-api.princeton.edu`. Princeton's only
  published OpenAPI (3.1.1), served by the application itself at `/api-docs/v1/swagger.yaml` with a
  Swagger UI at `/api-docs`. 14 operations, all with operationId/summary/description/tags; all 32
  response media types carry an example. Open source: https://github.com/pulibrary/allsearch_api
- **Princeton University Art Museum API** — `data.artmuseum.princeton.edu`. Open, no-auth REST for
  objects, makers, packages and full-text search. Prose docs only; the OpenAPI here is *derived*.
- **Princeton OIT API Gateway** — `api.princeton.edu`. WSO2 API Manager fronting ActiveDirectory,
  PrincetonInfo, MobileApp (course/dining/places) and LibAlma. NetID/service-account gated (401).
- **Library Catalog (Orangelight)** — `catalog.princeton.edu/catalog.json`
- **Bibdata** — `bibdata.princeton.edu`, PUL's own bibliographic data web service
- **Figgy** — `figgy.princeton.edu/oai`, a verified OAI-PMH 2.0 endpoint, plus IIIF
- **Princeton Data Commons** — `datacommons.princeton.edu/discovery`, institution-operated research
  data repository with DataCite DOIs under Princeton's own 10.34770 prefix
- **DataSpace** — `dataspace.princeton.edu`, DSpace repository on PUL's own cloud estate
- **Finding Aids (PULFAlight)** — `findingaids.princeton.edu`
- **Maps (PUL Map / GeoBlacklight)** — `maps.princeton.edu`
- **Digital PUL** — `dpul.princeton.edu`
- **Shibboleth Identity Provider** — `idp.princeton.edu/idp/shibboleth`, published SAML 2.0 metadata

### tenant (2)

- **Ex Libris Alma / Primo VE** (`01PRI_INST`) — the library management and discovery layer
- **Canvas LMS** — `princeton.instructure.com`

No vendor-operated contract is saved under this slug. `princeton.figshare.com` was probed and
rejected: a nonsense subdomain returns the same empty 202 from the same load balancer, so there is
no Figshare tenancy here.

## Education-regime conformance

Verified against machine-readable artifacts, not prose claims:

| Standard | Evidence |
|---|---|
| `oai-pmh` | `figgy.princeton.edu/oai?verb=Identify` → 200, valid OAI-PMH 2.0 Identify |
| `shibboleth` | `idp.princeton.edu/idp/shibboleth` → SAML EntityDescriptor with Shibboleth protocol support |
| `saml` | Same document — SAML 1.1 + 2.0 SSO and SLO endpoints, signing/encryption keys |
| `datacite` | Three registered DataCite clients: `pu.dataspace`, `pu.tigerdata`, `pu.openpublishing` |
| `orcid` | `orcid.princeton.edu` (pulibrary/orcid_princeton); ORCID iDs in PDC discovery records |

## Artifacts

- OpenAPI: [openapi/](openapi/) — plus [openapi/_original/](openapi/_original/) pristine copies
- JSON Schema: [json-schema/](json-schema/)
- Examples (verbatim captured responses): [examples/](examples/)
- Conformance: [conformance/princeton-conformance.yml](conformance/princeton-conformance.yml)
- Authentication: [authentication/princeton-authentication.yml](authentication/princeton-authentication.yml)
- Errors: [errors/princeton-errors.yml](errors/princeton-errors.yml)
- Scopes: [scopes/princeton-scopes.yml](scopes/princeton-scopes.yml)
- Lifecycle: [lifecycle/princeton-lifecycle.yml](lifecycle/princeton-lifecycle.yml)
- Spectral rules: [rules/princeton-openapi-spectral-rules.yml](rules/princeton-openapi-spectral-rules.yml)
- Vocabulary: [vocabulary/princeton-vocabulary.yml](vocabulary/princeton-vocabulary.yml)
- Plans: [plans/princeton-plans-pricing.yml](plans/princeton-plans-pricing.yml)
- Rate limits: [rate-limits/princeton-rate-limits.yml](rate-limits/princeton-rate-limits.yml)
- FinOps: [finops/princeton-finops.yml](finops/princeton-finops.yml)
- Review: [review.yml](review.yml)

## What the June 2026 profile got wrong

1. It missed the Allsearch API entirely — Princeton's only published OpenAPI.
2. It missed the Shibboleth IdP metadata, the Figgy OAI-PMH endpoint, Bibdata, Princeton Data
   Commons and the whole Blacklight discovery family.
3. It listed `api-store.princeton.edu` as a live developer portal. That host no longer resolves
   (NXDOMAIN as of 2026-08-19) and the pointer has been removed.
4. It read DataSpace's HTTP 401 as "requires authentication". It is Princeton's own in-house ALTCHA
   proof-of-work bot challenge (`pulibrary/altcha_rust_server`) — a client-verification gate, not an
   auth requirement.

## Coverage

`covered`. Twelve institution-operated surfaces reached with real probes. Not readable: every
Drupal-hosted `princeton.edu` marketing site (`library.`, `oit.`, `ai.`, `researchcomputing.`) sits
behind a Cloudflare JS interstitial returning 403 to non-browser clients even with full browser
headers, so no AIPolicy or ResearchComputing pointer is emitted; and DataSpace is behind the ALTCHA
challenge above. Both are blocks on our side, not gaps in Princeton's publishing.

## Timestamps

- Created: 2026-06-03
- Modified: 2026-08-19

## Maintainers

- Kin Lane — kin@apievangelist.com
