# Nextcloud (nextcloud)

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

Nextcloud is an open-source, self-hosted productivity platform offering file sync and share, collaboration, communication (Talk, Mail, Calendar, Contacts), and office (Nextcloud Office) features as a privacy-focused alternative to public cloud suites. Hosted in private datacenters or on-premises, Nextcloud is widely used by enterprises, governments, and individuals. The Nextcloud APIs include OCS REST APIs, WebDAV for file/folder operations, CalDAV/CardDAV, and an OpenAPI-described developer surface for apps and integrations.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/nextcloud/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/nextcloud/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- File Sync
- File Sharing
- Collaboration
- Self-Hosted
- Open Source
- Productivity
- WebDAV

## Timestamps

- **Created:** 2026-05-11
- **Modified:** 2026-05-11

## APIs

### Nextcloud OCS API

Open Collaboration Services REST API for managing shares, users, groups, capabilities, status, notifications, activities, and other Nextcloud server resources. Uses Basic Auth, app passwords, or OAuth-style login flows; results returned as JSON or XML.

- **Human URL:** [https://docs.nextcloud.com/server/latest/developer_manual/client_apis/OCS/ocs-api-overview.html](https://docs.nextcloud.com/server/latest/developer_manual/client_apis/OCS/ocs-api-overview.html)
- **Base URL:** `https://your-nextcloud.example/ocs/v2.php`

#### Tags

- OCS
- Shares
- Users
- Groups
- Notifications

#### Properties

- [Documentation](https://docs.nextcloud.com/server/latest/developer_manual/client_apis/OCS/ocs-api-overview.html)
- [Open A P I  Tutorial](https://docs.nextcloud.com/server/latest/developer_manual/digging_deeper/api/openapi.html)
- [Postman Collection](collections/nextcloud.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/nextcloud.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Nextcloud WebDAV API

WebDAV interface for files, folders, chunked uploads, trashbin, versions, comments, and search on a Nextcloud server. Provides the primary file-sync protocol used by Nextcloud desktop and mobile clients.

- **Human URL:** [https://docs.nextcloud.com/server/latest/developer_manual/client_apis/WebDAV/index.html](https://docs.nextcloud.com/server/latest/developer_manual/client_apis/WebDAV/index.html)
- **Base URL:** `https://your-nextcloud.example/remote.php/dav`

#### Tags

- WebDAV
- Files
- Sync
- Chunked Upload

#### Properties

- [Documentation](https://docs.nextcloud.com/server/latest/developer_manual/client_apis/WebDAV/index.html)
- [Postman Collection](collections/nextcloud.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/nextcloud.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/nextcloud-gmbh)
- [Website](https://nextcloud.com)
- [Documentation](https://docs.nextcloud.com)
- [Developer  Manual](https://docs.nextcloud.com/server/latest/developer_manual/)
- [Pricing](https://nextcloud.com/pricing/)
- [Sign Up](https://nextcloud.com/sign-up/)
- [Support](https://nextcloud.com/support/)
- [Blog](https://nextcloud.com/blog/)
- [GitHub Organization](https://github.com/nextcloud)
- [Git Hub  Server](https://github.com/nextcloud/server)
- [App  Store](https://apps.nextcloud.com)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
