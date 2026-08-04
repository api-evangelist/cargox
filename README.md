# Cargo X

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

Cargo X (CargoX) is a Sao Paulo based Brazilian logistics technology and fintech company, founded in 2013, that operates one of Brazil's largest digital freight marketplaces — matching shippers (embarcadores) with carriers (transportadoras) and independent truck drivers. Alongside freight brokerage it provides dedicated freight desk operations, driver qualification and real-time cargo monitoring, automated issuance of Brazilian transport tax documents (CT-e and MDF-e), cargo insurance, receivables financing and working-capital credit for carriers, and green-freight / ESG programs. It became a unicorn with a USD 200M Series F in October 2021 co-led by Tencent and SoftBank.

- https://cargox.com.br/
- https://cargox.com.br/blog/
- https://www.linkedin.com/company/cargoxbr
- https://www.hiive.com/securities/cargox-stock

## Disambiguation

Two unrelated companies use the CargoX name. This repo profiles **Cargo X of Brazil (cargox.com.br)**.
It is **not** CargoX of Slovenia (cargox.io / cargox.digital), the blockchain document transfer and
electronic bill of lading company — that company publishes its own REST API, Swagger schemas and a
Postman collection at developer.cargox.digital and warrants a separate provider repo keyed to its own
domain.

## API surface

As of 2026-08-02, Cargo X (Brazil) publishes **no public developer program** — no developer portal, API
reference, OpenAPI/Swagger, GraphQL endpoint, MCP server, A2A agent card, SDK, or public GitHub
organization. Negative evidence from the discovery probes is recorded in `well-known/` and in the
`x-contract-discovery` block of `apis.yml`.
