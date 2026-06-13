# Affinity (affinity)

Affinity is a relationship intelligence CRM built for private equity, venture capital, and investment banking teams. It provides a REST API that enables developers to manage contacts, organizations, opportunities, lists, notes, and relationship timelines derived from email and calendar activity. The API is available in two versions: a legacy V1 with full read/write capabilities for persons, companies, opportunities, notes, interactions, reminders, and webhooks, and a modern V2 RESTful interface designed for internal apps, automated workflows, and third-party integrations. API access is included in the Scale, Advanced, and Enterprise subscription tiers, with monthly call limits ranging from 100,000 to unlimited depending on the plan.

- **APIs.json:** https://raw.githubusercontent.com/api-evangelist/affinity/refs/heads/main/apis.yml
- **Naftiko:** https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=affinity-api-evangelist&utm_content=repo

## Tags

- CRM
- Relationship Intelligence
- Private Equity
- Venture Capital
- Contacts
- Organizations
- Opportunities
- Deal Management

## APIs

### Affinity API V1
The legacy Affinity V1 API provides comprehensive read and write access to core CRM data including persons, organizations, opportunities, lists, notes, interactions, reminders, and webhooks. It uses HTTP Basic Auth or Bearer Auth with an API key obtained from the Affinity Settings dashboard.

- **Documentation:** https://api-docs.affinity.co/
- **Base URL:** https://api.affinity.co

### Affinity API V2
The modern Affinity V2 API is a RESTful interface for building internal apps, automated workflows, and third-party integrations. It supports reading and writing data about people, companies, and opportunities, with Bearer Auth authentication. It is the actively developed version and includes a hosted MCP server integration for AI-powered workflows.

- **Documentation:** https://developer.affinity.co/
- **Base URL:** https://api.affinity.co

## Plans / Rate Limits / FinOps

- **Plans & Pricing:** [plans/affinity-plans-pricing.yml](plans/affinity-plans-pricing.yml)
- **Rate Limits:** [rate-limits/affinity-rate-limits.yml](rate-limits/affinity-rate-limits.yml)
- **FinOps:** [finops/affinity-finops.yml](finops/affinity-finops.yml)

### Plan Summary

| Plan | Price | API Calls/Month |
|------|-------|----------------|
| Essential | $2,000/user/year | None |
| Scale | $2,300/user/year | 100,000 |
| Advanced | $2,700/user/year | 100,000 |
| Enterprise | Custom | Unlimited |

### Rate Limit Summary

- 900 requests per user per minute (all plans)
- 100,000 calls per month (Scale and Advanced)
- Unlimited calls per month (Enterprise)
- 429 status code returned when limits are exceeded

## Timestamps

- **Created:** 2026-06-12
- **Modified:** 2026-06-12

## Common

| Type | URL |
|------|-----|
| Website | https://www.affinity.co/ |
| Documentation | https://developer.affinity.co/ |
| GitHub Org | https://github.com/affinity |
| LinkedIn | https://www.linkedin.com/company/project-affinity |
| Blog | https://www.affinity.co/resources/blog |
| Pricing | https://www.affinity.co/product/affinity-pricing |
| Status Page | https://status.affinity.co/ |
| X | https://x.com/affinity |

## Maintainers

- **Kin Lane** - kin@apievangelist.com
