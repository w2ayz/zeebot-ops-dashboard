# zeebot-ops-dashboard

Auto-synced copy of the service-health dashboard HTML for w2ayz's Mac mini ("Zeebot").

`checklist.html` here is overwritten on every hourly health-check run by
[slack-ops-monitor](https://github.com/w2ayz/slack-ops-monitor) via
`scripts/health_check.py`. It exists purely so a scheduled claude.ai cloud
routine can fetch it over `raw.githubusercontent.com` (which is reachable
from the cloud sandbox's network egress allowlist — gists and the GitHub
API are not) and republish it to the real Claude artifact dashboard.

Not meant to be browsed directly — the live dashboard is the published
Claude artifact this content gets pushed to.
