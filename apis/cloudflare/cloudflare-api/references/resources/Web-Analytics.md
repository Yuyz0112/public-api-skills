# Web Analytics

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| POST | `/accounts/{account_id}/rum/site_info` | Create a Web Analytics site | [View](../operations/web-analytics-create-site.md) |
| GET | `/accounts/{account_id}/rum/site_info/list` | List Web Analytics sites | [View](../operations/web-analytics-list-sites.md) |
| GET | `/accounts/{account_id}/rum/site_info/{site_id}` | Get a Web Analytics site | [View](../operations/web-analytics-get-site.md) |
| PUT | `/accounts/{account_id}/rum/site_info/{site_id}` | Update a Web Analytics site | [View](../operations/web-analytics-update-site.md) |
| DELETE | `/accounts/{account_id}/rum/site_info/{site_id}` | Delete a Web Analytics site | [View](../operations/web-analytics-delete-site.md) |
| POST | `/accounts/{account_id}/rum/v2/{ruleset_id}/rule` | Create a Web Analytics rule | [View](../operations/web-analytics-create-rule.md) |
| PUT | `/accounts/{account_id}/rum/v2/{ruleset_id}/rule/{rule_id}` | Update a Web Analytics rule | [View](../operations/web-analytics-update-rule.md) |
| DELETE | `/accounts/{account_id}/rum/v2/{ruleset_id}/rule/{rule_id}` | Delete a Web Analytics rule | [View](../operations/web-analytics-delete-rule.md) |
| GET | `/accounts/{account_id}/rum/v2/{ruleset_id}/rules` | List rules in Web Analytics ruleset | [View](../operations/web-analytics-list-rules.md) |
| POST | `/accounts/{account_id}/rum/v2/{ruleset_id}/rules` | Update Web Analytics rules | [View](../operations/web-analytics-modify-rules.md) |
| GET | `/zones/{zone_id}/settings/rum` | Get RUM status for a zone | [View](../operations/web-analytics-get-rum-status.md) |
| PATCH | `/zones/{zone_id}/settings/rum` | Toggle RUM on/off for a zone | [View](../operations/web-analytics-toggle-rum.md) |
