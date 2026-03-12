# mpcp-protocol.github.io

Unified documentation site for the Machine Payment Control Protocol (MPCP).

**URL:** https://mpcp-protocol.github.io/

**Structure:**
- `/` — Landing page
- `/spec/` — Protocol specification (from [mpcp-spec](https://github.com/mpcp-protocol/mpcp-spec))
- `/reference/` — Reference implementation docs (from [mpcp-reference](https://github.com/mpcp-protocol/mpcp-reference))

## Setup

1. Create the `mpcp-protocol.github.io` repository in the mpcp-protocol organization.
2. Push this content to `main`.
3. GitHub Settings → Pages → Source: **GitHub Actions**
4. Run the "Deploy Docs" workflow (runs on push to `main`, or manually).
4. The deploy workflow builds both sites and publishes on push to `main` or via manual trigger.
