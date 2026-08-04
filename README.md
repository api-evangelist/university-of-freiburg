# University of Freiburg (university-of-freiburg)

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
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

The University of Freiburg (Albert-Ludwigs-Universität Freiburg) is a public research university in Freiburg im Breisgau, Germany, founded in 1457 and ranked #212 in the QS World University Rankings 2025. It has no centralized public developer portal, but its university library exposes several real, publicly reachable read APIs for research metadata and data.

- APIs.json: https://raw.githubusercontent.com/api-evangelist/university-of-freiburg/refs/heads/main/apis.yml
- Run with Naftiko: https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=university-of-freiburg-api-evangelist&utm_content=repo

## Type

Index / Consumer / 3rd-Party

## Tags

Education, Higher Education, University, Research, Open Data, Library, Germany

## APIs

- **FreiDok plus JSON API** — Read-only JSON API for the FreiDok plus institutional repository and university bibliography. Docs: https://freidok.uni-freiburg.de/_/site/about (base: `https://freidok.uni-freiburg.de/jsonApi/v1/`)
- **FreiDok plus OAI-PMH** — OAI-PMH 2.0 metadata-harvesting endpoint (oai_dc, marcxml, xMetaDissPlus, and more). Docs: https://freidok.uni-freiburg.de/oai/oai2.php?verb=Identify (base: `https://freidok.uni-freiburg.de/oai/oai2.php`)
- **FreiData InvenioRDM REST API** — REST API for the FreiData research-data repository. Docs: https://freidata.uni-freiburg.de/ (base: `https://freidata.uni-freiburg.de/api/`)

## Plans

- [plans/university-of-freiburg-plans-pricing.yml](plans/university-of-freiburg-plans-pricing.yml)

## Rate Limits

- [rate-limits/university-of-freiburg-rate-limits.yml](rate-limits/university-of-freiburg-rate-limits.yml)

## FinOps

- [finops/university-of-freiburg-finops.yml](finops/university-of-freiburg-finops.yml)

## Timestamps

- Created: 2026-06-03
- Modified: 2026-06-03

## Common Properties

- Website: https://www.uni-freiburg.de/
- LinkedIn: https://www.linkedin.com/school/albert-ludwigs-universitaet-freiburg/
- Plans, Rate Limits, FinOps, Review (see files above and [review.yml](review.yml))

## Notes

All three APIs were probed live on 2026-06-03 and returned HTTP 200 with JSON/XML payloads. No official University of Freiburg GitHub organization exists — github.com/uni-freiburg is an unofficial student account (zero repos, explicit disclaimer) and was deliberately excluded. No endpoints were fabricated; baseURLs reflect only confirmed, publicly reachable interfaces. The university does not publish a formal developer program, signup, or authentication flow for these open read endpoints.

## Maintainers

- Kin Lane — kin@apievangelist.com
