# Runc (runc)
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
