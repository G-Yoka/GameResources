# OpenSteamTool Game Resources

Resource manifest repository for OpenSteamTool Manager.

## Structure

- `manifest.json`: package index consumed by OpenSteamTool Manager.
- `packages/`: ZIP assets referenced by the manifest.

## Package rule

Each package must include a SHA-256 hash in `manifest.json`. The manager verifies the hash before installing.
