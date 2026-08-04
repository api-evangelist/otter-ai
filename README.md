# Otter.ai (otter-ai)

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

Otter.ai is an AI-powered meeting transcription and conversational intelligence platform that automatically records, transcribes, and summarizes meetings across Zoom, Google Meet, Microsoft Teams, and other video conferencing services. The platform provides a REST API for Enterprise customers to programmatically retrieve speech-to-text transcripts, speaker-identified conversation segments, and AI-generated meeting summaries. Developers can upload audio files, retrieve processed transcripts via webhooks, and integrate meeting intelligence into their own applications using bearer token authentication. Otter.ai also offers an MCP Server integration enabling AI assistants like Claude and ChatGPT to query meeting knowledge directly.

APIs.json: https://raw.githubusercontent.com/api-evangelist/otter-ai/refs/heads/main/apis.yml

Naftiko: https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=otter-ai-api-evangelist&utm_content=repo

## Tags

- AI
- Transcription
- Meeting Notes
- Speech-to-Text
- Speaker Identification
- Meeting Intelligence
- Summaries

## APIs

- **Otter.ai API** — REST API for Enterprise customers to upload audio/video files, retrieve speaker-identified transcripts, and receive webhook notifications on speech processing completion. Uses bearer token authentication. Docs: https://otter.ai/api/docs/

## Plans, Rate Limits, and FinOps

- **Plans/Pricing**: [plans/otter-ai-plans-pricing.yml](plans/otter-ai-plans-pricing.yml) — Four tiers: Basic (free), Pro ($8.33–$16.99/user/mo), Business ($19.99–$30/user/mo), Enterprise (custom). API access is Enterprise only.
- **Rate Limits**: [rate-limits/otter-ai-rate-limits.yml](rate-limits/otter-ai-rate-limits.yml) — Pro: 60 req/min; Enterprise: 500 req/min. Transcription minute caps vary per plan.
- **FinOps**: [finops/otter-ai-finops.yml](finops/otter-ai-finops.yml) — FOCUS-aligned cost allocation, optimization, and forecasting guidance for Otter.ai seat and API spend.

## Timestamps

- Created: 2026-06-13
- Modified: 2026-06-13

## Common

| Type | URL |
|------|-----|
| Website | https://otter.ai |
| Documentation | https://otter.ai/api/docs/ |
| GitHub Org | https://github.com/otter-framework |
| LinkedIn | https://www.linkedin.com/company/otter-ai |
| Blog | https://otter.ai/blog |
| Pricing | https://otter.ai/pricing |
| Status Page | https://status.otter.ai/ |
| X | https://x.com/otter_ai |

## Maintainers

- **Kin Lane** — kin@apievangelist.com
