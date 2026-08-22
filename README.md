# Recognise Bank (recognise-bank)

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
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

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
