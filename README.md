# CIBC (cibc)

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

Canadian Imperial Bank of Commerce (CIBC) is a Schedule I domestic chartered bank and one of Canada's Big Six, formed in 1961 through the merger of the Canadian Bank of Commerce and the Imperial Bank of Canada and headquartered in Toronto, Ontario. It serves roughly eleven million clients across Personal & Business Banking, Wealth Management, and Capital Markets.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/cibc/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/cibc/refs/heads/main/apis.yml)

## Open-Finance Posture

Canada has **no operational open-banking mandate** today. The federal **Consumer-Driven Banking** framework — legislated in Budget 2024 and the 2024 Fall Economic Statement, overseen by the Financial Consumer Agency of Canada (FCAC) — is on the books but not yet live, so access remains voluntary and fragmented.

Against that backdrop, CIBC's honest public API posture is:

- **No first-party public developer portal.** `developer.cibc.com` does not resolve (DNS/connection failure), and CIBC publishes no downloadable OpenAPI or Swagger specifications.
- **Aggregator-mediated consumer data access.** CIBC signed a tokenized data-access agreement with U.S. aggregator **MX** (announced August 2022 — MX's first such deal in Canada) so clients can share financial data with third-party apps without exposing banking credentials. CIBC accounts are also reachable through **Plaid** (Assets, Auth, Balance).
- **Corporate connectivity via SWIFT, not REST.** Business/treasury customers exchange files through **CIBC SWIFT Corporate Access (SCA)** rather than a public web API.
- **Shared Canadian rails.** CIBC participates in **Interac** e-Transfer and Payments Canada settlement systems, but exposes no public API around them.
- **Not a documented FDX first-party participant** with published specs, and no self-service OAuth developer flow is documented.

The result: CIBC's public API surface today is **aggregator-mediated only**, pending the coming Consumer-Driven Banking regime.

> Note: **CIBC Bank USA** (the U.S. subsidiary, `us.cibc.com`) is a separate legal entity profiled in the distinct `cibc-us` repository. This repository covers the **Canadian parent**, Canadian Imperial Bank of Commerce.

## Tags

- Financial Services
- Banking
- Canada
- Big Six
- Schedule I Bank
- Open Finance
- Consumer-Driven Banking
- Interac
- Payments
- Data Aggregation

## Timestamps

- **Created:** 2026-07-23
- **Modified:** 2026-07-23

## APIs

No first-party public developer APIs are documented. Consumer-permissioned account and balance data is available only through third-party aggregators (MX, Plaid).

## Common Properties

- [Website](https://www.cibc.com)
- [About](https://www.cibc.com/en/about-cibc.html)
- [GitHub Organization](https://github.com/cibc)
- [LinkedIn](https://www.linkedin.com/company/cibc)
- [Documentation (Cash Management Services)](https://www.cibc.com/en/commercial/business-solutions/managing-cash-flow/cash-management-services.html)
- [Privacy Policy](https://www.cibc.com/en/privacy-security/privacy-policy.html)
- [Terms of Service](https://www.cibc.com/en/legal.html)
- [Data Aggregator (Plaid)](https://plaid.com/institutions/cibc/)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
