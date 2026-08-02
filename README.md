# Formation Bio

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
