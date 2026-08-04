# Formation Bio

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

Formation Bio (formerly TrialSpark, rebranded December 2023) is a New York-based, tech-driven, AI-native pharmaceutical company co-founded by Ben Liu and Linhao Zhang. Rather than discovering molecules, it in-licenses and acquires clinical-stage drug assets and runs them through a proprietary AI and software development engine — Delphi, Atlas, Forge, Apollo, ARK and a unified Data Platform — plus Muse, an AI patient-recruitment system built with Sanofi and OpenAI.

- Website: https://www.formation.bio/
- Technology: https://www.formation.bio/technology
- GitHub: https://github.com/trialspark
- Secondary market listing: https://forgeglobal.com/trialspark_stock/

## API surface

**None public.** Contract discovery on 2026-07-31 found no OpenAPI, no GraphQL, no MCP server, no A2A agent card, no AsyncAPI and no documented webhooks, and no developer portal or API documentation. Formation Bio's platform is internal-facing. See `x-contract-discovery` in `apis.yml` and `well-known/trialspark-well-known.yml` for the full probe table.

## Artifacts

- `packages/` — four first-party open-source packages published under the `trialspark` GitHub org to npm/PyPI. None is an API client SDK.
- `well-known/` — `/.well-known/` probe index (all 404).
- `llms/` — generated `llms.txt`.
- `security/` — probed TLS/HSTS/DNSSEC/CAA/SPF/DMARC posture.
