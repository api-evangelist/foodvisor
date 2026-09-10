# Foodvisor (foodvisor)

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

Foodvisor is a French mobile nutrition platform whose app identifies food items from a
photograph using computer vision and returns calories, macronutrients and portion
estimates. Between 2023 and 2025 Foodvisor also sold that capability to developers as the
**Foodvisor Vision API**. That developer product has been withdrawn.

**APIs.json:** [apis.yml](https://raw.githubusercontent.com/api-evangelist/foodvisor/refs/heads/main/apis.yml)

## API program status: retired

As measured on **2026-09-10**:

| Surface | Result |
| --- | --- |
| `https://www.foodvisor.io/en/vision/` (Vision API product page) | **HTTP 404** |
| `vision.foodvisor.io` (documentation host) | **NXDOMAIN** from three independent resolvers |
| Live site route table | no `/vision/`, `/api/` or `/developers/` route among 23 declared routes |
| Site translation bundle (78 KB) | zero occurrences of *vision*, *developer*, *docs*, *enterprise*, *business* |
| OpenAPI / Swagger / GraphQL / AsyncAPI / WSDL / Protobuf | none published on any host |
| `/.well-known/*` (4 hosts x 8 paths) | every path 404 or 403 |
| `llms.txt` | 404 |
| MCP server, A2A agent card | none |
| Client SDKs (npm, PyPI, RubyGems, crates.io, Packagist, GitHub org) | none |

Internet Archive captures put the withdrawal between **2025-11-08** (last HTTP 200) and
**2026-01-08** (first HTTP 404). No sunset notice, deprecation policy, migration guide or
replacement endpoint was published. The dated evidence is in
[`lifecycle/foodvisor-lifecycle.yml`](lifecycle/foodvisor-lifecycle.yml).

The company itself is active — only the developer program is gone.

## Scope

- **Type:** Index
- **Position:** Consuming
- **Access:** 3rd-Party

## Tags

Artificial Intelligence, Computer-Vision, Food, Health, Nutrition, Mobile

## APIs

### Foodvisor Vision API (retired)

A commercial computer-vision API that detected food items in a photograph and returned
nutritional facts. Endpoint and authentication details were issued to customers under a
commercial agreement and no public OpenAPI specification was ever published. No `baseURL`
is recorded, because Foodvisor never published one to a public URL that survives and this
profile does not infer one from the mobile app or from third-party wrappers.

## Common Properties

- [Website](https://www.foodvisor.io/)
- [GitHub Organization](https://github.com/Foodvisor)
- [LinkedIn](https://www.linkedin.com/company/foodvisor)
- [Terms of Service](https://www.foodvisor.io/en/terms-of-service/)
- [Privacy Policy](https://www.foodvisor.io/en/privacy-policy/)
- [Sign Up](https://www.foodvisor.io/en/signup/)

Every link above returned HTTP 200 on 2026-09-10. The previous `Documentation` and
`Contact Sales` pointers both resolved to `https://www.foodvisor.io/en/vision/`, which now
returns 404; they have been removed rather than left standing as claims Foodvisor no longer
supports.

## Maintainers

- **FN:** Kin Lane
- **Email:** kin@apievangelist.com
