# 7YA.io — AppDeploy Production Mirror

This repository is the clean source mirror for the live AppDeploy application serving **7ya.io**.

- Live runtime: AppDeploy app `697a008fddc309b142`
- Production domain: `7ya.io` / `www.7ya.io`
- AI reasoning provider: NVIDIA via backend-only `NVIDIA_API_KEY`
- Evidence rule: metrics remain source-local and dated; external/derivative reach is never silently added to owned-account metrics.

## Current cutover

Production snapshot: `1787768270311` (2026-08-26)

This mirror is being rebuilt from the live AppDeploy snapshot. The files under `production-snapshot/` are authoritative exports from that applied snapshot; do not treat the older `7guard-io/7ya.io` GitHub Pages workflow as the live production deploy path.
