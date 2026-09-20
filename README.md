# Parcae — container images

This repository only exists to publish Parcae's container images to the
GitHub Container Registry. It carries no source code and accepts no
contributions.

- **Source, issues and pull requests:** https://tangled.org/tielbeke.io/parcae
- **Website:** https://parcae.eu
- **Image:** `ghcr.io/antoinetielbeke/parcae`

```bash
docker pull ghcr.io/antoinetielbeke/parcae:latest
```

Parcae is an open-source Identity Governance & Administration layer for
self-hosted OIDC identity providers (Authentik, Keycloak): users request
access to groups, approvers decide, Parcae provisions and expires the
membership and keeps an append-only audit trail.

The canonical registry is European; this one is a convenience copy.
Licensed under the terms in [LICENSE](LICENSE).
