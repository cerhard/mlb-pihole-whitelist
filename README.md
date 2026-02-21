# MLB.tv Pi-hole Whitelist

This repository contains a list of domains intended to be whitelisted in Pi-hole so that MLB.tv (the MLB streaming service) functions correctly.

Files
- `mlb-whitelist-hosts.txt` — newline-separated domains to whitelist (comments allowed with `#`).


Usage

1. Pi-hole Web UI (recommended):
  - Open the Pi-hole Admin Console.
  - Go to "Lists" (in some versions this is under `Settings` or `Group Management`).
  - In the Allowlist section, choose the option to add/import from URL.
  - Paste this URL:

    https://raw.githubusercontent.com/cerhard/mlb-pihole-whitelist/refs/heads/main/mlb-whitelist-hosts.txt

  - Click "Add Allowlist" to import and enable the domains.

2. Alternative: Download and import manually
  - Download `mlb-whitelist-hosts.txt` and use the web UI import or run `pihole -w` on the Pi-hole host if you prefer a manual method.

