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
3. **Configure Pages** (critical for /spec and /reference to work):
   - Repo **Settings** → **Pages**
   - **Build and deployment** → **Source**: **Deploy from a branch**
   - **Branch**: `gh-pages` (not `main`)
   - **Folder**: `/ (root)`
4. Run **Actions** → **Deploy Docs** (runs on push to `main`, or trigger manually).
