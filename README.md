# Recognise Bank (recognise-bank)

Recognise Bank Limited is a UK challenger bank focused on the SME sector and the personal and business savings markets, offering fixed-rate, notice, and easy-access savings accounts alongside secured SME lending such as bridging loans and commercial mortgages. Formed out of AIM-listed City of London Group and now majority owned by Gibraltar-based Parasol V27 Limited, it is authorised by the Prudential Regulation Authority and regulated by the Financial Conduct Authority under FRN 849404, with deposits protected by the FSCS.

As a deposit-and-lending institution that does not offer payment/current accounts, Recognise Bank is not one of the CMA9 and publishes no dedicated developer portal, Open Banking Open Data endpoint, or Read/Write API surface at review time. The UK Open Banking (OBIE / PSD2) API families below are represented as the shared industry standard the bank would conform to if it exposed regulated account and payment interfaces — not as confirmed Recognise-operated endpoints.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/recognise-bank/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/recognise-bank/refs/heads/main/apis.yml)

## Tags

- Financial Services
- Banking
- Open Banking
- PSD2
- OBIE
- United Kingdom
- Savings
- SME Lending
- Fintech
- Account Information

## Timestamps

- **Created:** 2026-07-23
- **Modified:** 2026-07-23

## APIs

> The following are the shared UK Open Banking (OBIE) standard specifications, harvested verbatim from the Open Banking UK repositories and clearly labelled as the industry standard. No Recognise Bank-specific host, developer portal, or confirmed endpoint was found; probes to standard Open Data paths on `recognisebank.co.uk` returned HTTP 404, and `api.` / `developer.` subdomains do not resolve.

### UK Open Banking Open Data API (OBIE Standard)

Shared UK Open Banking Open Data standard for public, unauthenticated reference data (ATMs, branches, personal and business current accounts, unsecured SME loans, commercial credit cards).

- **Human URL:** [https://github.com/OpenBankingUK/opendata-api-spec-compiled](https://github.com/OpenBankingUK/opendata-api-spec-compiled)
- **Base URL (standard path):** `/open-banking/v2.3`

#### Tags

- Open Data
- Reference Data

#### Properties

- [OpenAPI](openapi/obie-opendata-swagger.json) — OBIE Open Data (Swagger 2.0), shared standard
- [Documentation](https://openbanking.org.uk/open-data-apis/)

### UK Open Banking Account & Transaction Information API (OBIE Standard)

Shared OBIE Read/Write Account & Transaction Information (AIS) standard, FAPI-secured with OAuth2/OIDC, mutual-TLS, and PSD2 strong customer authentication.

- **Human URL:** [https://github.com/OpenBankingUK/read-write-api-specs](https://github.com/OpenBankingUK/read-write-api-specs)
- **Base URL (standard path):** `/open-banking/v4.0/aisp`

#### Tags

- Account Information
- AIS

#### Properties

- [OpenAPI](openapi/obie-account-info-openapi.yaml) — OBIE Read/Write AIS v4.0, shared standard
- [Documentation](https://openbankinguk.github.io/read-write-api-site3/)

### UK Open Banking Payment Initiation API (OBIE Standard)

Shared OBIE Read/Write Payment Initiation (PIS) standard, FAPI-secured with OAuth2/OIDC, mutual-TLS, and PSD2 SCA.

- **Human URL:** [https://github.com/OpenBankingUK/read-write-api-specs](https://github.com/OpenBankingUK/read-write-api-specs)
- **Base URL (standard path):** `/open-banking/v4.0/pisp`

#### Tags

- Payment Initiation
- PIS

#### Properties

- [OpenAPI](openapi/obie-payment-initiation-openapi.yaml) — OBIE Read/Write PIS v4.0, shared standard
- [Documentation](https://openbankinguk.github.io/read-write-api-site3/)

### UK Open Banking Confirmation of Funds API (OBIE Standard)

Shared OBIE Read/Write Confirmation of Funds (CBPII) standard, FAPI-secured with OAuth2/OIDC, mutual-TLS, and PSD2 SCA.

- **Human URL:** [https://github.com/OpenBankingUK/read-write-api-specs](https://github.com/OpenBankingUK/read-write-api-specs)
- **Base URL (standard path):** `/open-banking/v4.0/cbpii`

#### Tags

- Confirmation of Funds
- CBPII

#### Properties

- [OpenAPI](openapi/obie-confirmation-funds-openapi.yaml) — OBIE Read/Write CBPII v4.0, shared standard
- [Documentation](https://openbankinguk.github.io/read-write-api-site3/)

## Common Properties

- [Website](https://recognisebank.co.uk/)
- [LinkedIn](https://www.linkedin.com/company/recognisebank/)
- [Blog](https://recognisebank.co.uk/blog/)
- [Blog RSS](https://recognisebank.co.uk/feed/)
- [Terms of Service](https://recognisebank.co.uk/terms-of-use/)
- [Privacy Policy](https://recognisebank.co.uk/privacy-notice/)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
