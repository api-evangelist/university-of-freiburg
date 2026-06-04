# University of Freiburg (university-of-freiburg)

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
