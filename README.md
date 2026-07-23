# CIBC (cibc)

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
