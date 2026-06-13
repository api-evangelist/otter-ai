# Otter.ai (otter-ai)

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
