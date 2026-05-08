# Sensible (sensible-io)

Sensible is a developer-focused document understanding platform that converts unstructured documents (PDFs, emails, images) into JSON. The core IP is SenseML, a document-specific query language combining LLM techniques with layout-based rules.

**APIs.json:** [apis.yml](apis.yml)

## APIs
- **Sensible REST API** — `https://api.sensible.so/v0` — extract (sync/async), classify, fill, generate, document/portfolio management. Bearer-token auth. [Docs](https://docs.sensible.so/reference/api-overview).

## OpenAPI
The Sensible REST API documentation is interactive (ReadMe-hosted) but a downloadable OpenAPI/Swagger document is not exposed at a public anonymous URL as of 2026-05-08; pipeline did not retrieve a spec into `openapi/`.

## Tags
AI, Document AI, IDP, Extraction, LLM, SenseML, PDF

## Common Properties
- [Website](https://www.sensible.so/) · [Docs](https://docs.sensible.so/) · [Pricing](https://www.sensible.so/pricing) · [GitHub](https://github.com/sensible-hq)
- [Plans](plans/sensible-io-plans-pricing.yml) — reconciled
- [Rate Limits](rate-limits/sensible-io-rate-limits.yml) — partially reconciled (per-second numeric limit not public; bundle/overage reconciled)
- [FinOps](finops/sensible-io-finops.yml) — reconciled, FOCUS-aligned

## Plans (reconciled)
- **Growth** — $499/mo (or $449/mo annual). 750 docs/mo + $0.50/doc overage.
- **Scale** — $1,499/mo (or $1,349/mo annual). 3,200 docs/mo + $0.50/doc overage; human review and document splitting.
- **Enterprise** — custom; 10K+ docs/mo, tiered overage, white-glove support.

## Timestamps
- **Created:** 2026-05-08
- **Modified:** 2026-05-08

## Maintainers
- **Kin Lane** — kin@apievangelist.com
