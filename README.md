# Helios

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

helios is a French sustainable-banking company (HELIOS SAS, Paris) offering current, Premium, joint, youth, Liberté and independent/professional accounts, a green savings passbook, sustainable life insurance and wooden or recycled-plastic Visa cards through iOS, Android and web. It is a société à mission and a certified B Corp whose promise is that no customer euro finances fossil fuels or polluting industry. helios is registered in REGAFI under 731225 as a payment services agent of OKALI, the ACPR-approved electronic money institution that services the accounts.

**No public API surface.** helios publishes no developer portal, API reference, SDK or webhook surface, and exposes no PSD2 dedicated interface of its own. The one machine-readable document it serves is [`/llms.txt`](https://www.helios.do/llms.txt) — a French-language AI-usage policy captured verbatim in [`llms/`](llms/). Every probe behind that finding is recorded in [`well-known/helios-well-known.yml`](well-known/helios-well-known.yml).

> **Not the same Helios.** This profile is helios.do, the French neobank. It is unrelated to helios.earth (NV5 Geospatial's weather API), Helios Climate Ventures, or any of the open-source projects named Helios. No contract from those hosts belongs here.

Source: portfolio company of [serena](https://github.com/api-evangelist/serena) — https://www.helios.do/
