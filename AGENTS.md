# Shopwell repository rules

This repository is the independently maintained Shopwell build-project Action.

- Preserve UTF-8 and existing user changes.
- Project-owned code and manifests use Apache License 2.0 (`Apache-2.0`); root `LICENSE` is the standard text.
- Preserve the upstream MIT text verbatim in root `NOTICE`; do not reintroduce Shopware branding outside legal text.
- Do not merge or cherry-pick upstream history, copy upstream tags, or force-push.
- Before reporting a successful sync, run `./bin/syncctl audit-license build-project-action`,
  `./bin/syncctl audit-repository-identity build-project-action`,
  `./bin/syncctl audit-dependency-parity build-project-action`, and
  `./bin/syncctl audit-upstream-dependencies build-project-action` from `/Users/goxs/Workspaces/shopwell/sync-upstream`.
