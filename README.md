# CricAPI (cricapi)

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

CricAPI is a cricket data API platform that has provided free, high-performance cricket data since September 2015, originally at cricapi.com and now operating as CricketData.org following an acquisition in December 2021. The API delivers live scores, ball-by-ball updates, match details, player statistics, team rankings, schedules, and fantasy cricket scorecard data for international and domestic tournaments including ICC events, IPL, T20I, BBL, and PSL. Historical match data is available back to 2000 and the platform is ISO 9001:2015 certified.

**APIs.json:** https://raw.githubusercontent.com/api-evangelist/cricapi/refs/heads/main/apis.yml

**Naftiko:** https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=cricapi-api-evangelist&utm_content=repo

## Tags

Cricket, Sports, Live Scores, Player Statistics, Match Data, Fantasy Cricket, Ball-by-Ball, Team Rankings, Schedules, Sports Data

## APIs

| Name | Description | Docs |
|------|-------------|------|
| Cricket Data API | Live scores, ball-by-ball updates, player statistics, match details, team rankings, schedules, historical data, and fantasy cricket endpoints | [Docs](https://cricketdata.org/how-to-use-cricket-data-api.aspx) |

## Plans, Rate Limits, and FinOps

CricAPI uses a flat-rate tiered billing model with no overage charges. Plans are differentiated by daily API hit quotas.

| Plan | Price/Month | Daily Hits |
|------|-------------|------------|
| Lifetime Free | $0.00 | 100 |
| Plan S | $5.99 | 2,000 |
| Plan M | $12.99 | 10,000 |
| Plan L | $29.99 | 100,000 |
| Plan U | $64.99 | Unlimited |

- **Plans:** [plans/cricapi-plans-pricing.yml](plans/cricapi-plans-pricing.yml)
- **Rate Limits:** [rate-limits/cricapi-rate-limits.yml](rate-limits/cricapi-rate-limits.yml)
- **FinOps:** [finops/cricapi-finops.yml](finops/cricapi-finops.yml)

Each API response includes in-band hit-count tracking. There are no contracts, and cancellation is instant.

## Timestamps

- **Created:** 2026-06-12
- **Modified:** 2026-06-12

## Common

| Type | URL |
|------|-----|
| Website | https://www.cricapi.com/ |
| Website | https://cricketdata.org/ |
| Documentation | https://cricketdata.org/how-to-use-cricket-data-api.aspx |
| Pricing | https://cricketdata.org/pricing/ |
| Blog | https://cricketdata.org/blog/ |
| Status Page | https://stats.uptimerobot.com/PpnXLf0Mpm |
| X / Twitter | https://twitter.com/cricapi |
| Forum | https://cricketdata.org/forum/ |
| Contact | https://cricketdata.org/contact/ |

## Maintainers

| Name | Email |
|------|-------|
| Kin Lane | kin@apievangelist.com |
