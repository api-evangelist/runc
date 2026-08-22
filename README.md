# Runc (runc)

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

runc is a CLI tool for spawning and running containers on Linux according to the OCI (Open Container Initiative) specification. It is the reference implementation of the OCI runtime specification and is used as the default low-level container runtime by Docker, containerd, Podman, and other container platforms. runc manages container lifecycle operations including creating, starting, pausing, resuming, killing, and deleting containers. It implements the OCI Runtime Specification and exposes a command-line interface that higher-level runtimes use to manage individual container instances. runc also supports checkpoint/restore via CRIU, rootless containers, cgroup v2, seccomp syscall filtering, AppArmor, and SELinux.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/runc/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags:

 - Container Runtime, Containers, Linux, OCI, Open Source, CNCF, Open Container Initiative, Cloud Native

## Timestamps

- **Created:** 2026-03-26
- **Modified:** 2026-05-02

## APIs

### Runc
runc is a CLI tool for spawning and running containers on Linux according to the OCI (Open Container Initiative) specification. It is the reference implementation of the OCI runtime specification, providing a lightweight and portable container runtime that can be used independently or embedded into higher-level container systems like Docker and containerd. runc implements the full OCI Runtime Spec lifecycle: create, start, state, kill, delete. It also supports checkpoint/restore via CRIU, rootless containers, and cgroup v2. The container configuration is defined in a config.json file following the OCI Runtime Specification schema.

**Human URL:** [https://github.com/opencontainers/runc](https://github.com/opencontainers/runc)

#### Tags:

 - Container Runtime, Containers, Linux, OCI, Open Source, CNCF, Open Container Initiative, Cloud Native

#### Properties

- [Documentation](https://github.com/opencontainers/runc/blob/main/README.md)
- [Getting Started](https://github.com/opencontainers/runc#creating-an-oci-bundle)
- [GitHub Repository](https://github.com/opencontainers/runc)
- [Specification](https://github.com/opencontainers/runtime-spec)
- [Releases](https://github.com/opencontainers/runc/releases)
- [License](https://github.com/opencontainers/runc/blob/main/LICENSE)
- [Security](https://github.com/opencontainers/runc/blob/main/SECURITY.md)
- [Changelog](https://github.com/opencontainers/runc/blob/main/CHANGELOG.md)
- [JSON Schema](json-schema/runc-container-config-schema.json)
- [JSON Structure](json-structure/runc-container-config-structure.json)
- [JSON-LD Context](json-ld/runc-context.jsonld)
- [Example Container Config](examples/runc-container-config-example.json)
- [Vocabulary](vocabulary/runc-vocabulary.yml)

## JSON Schema

- [OCI Runtime Container Configuration Schema](json-schema/runc-container-config-schema.json)

## JSON Structure

- [OCI Runtime Container Configuration Structure](json-structure/runc-container-config-structure.json)

## JSON-LD

- [Runc JSON-LD Context](json-ld/runc-context.jsonld)

## Examples

- [Example OCI Container Config (config.json)](examples/runc-container-config-example.json)

## Vocabulary

- [Runc and OCI Container Runtime Vocabulary](vocabulary/runc-vocabulary.yml)

## Common Properties

- [Website](https://opencontainers.org/)
- [GitHub Organization](https://github.com/opencontainers)
- [GitHub Repository](https://github.com/opencontainers/runc)
- [Blog](https://opencontainers.org/posts/blog/)
- [Documentation](https://github.com/opencontainers/runc/blob/main/README.md)
- [Specification](https://github.com/opencontainers/runtime-spec)
- [Security](https://github.com/opencontainers/runc/blob/main/SECURITY.md)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
