# firewall_country_configuration

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `target` | enum: country | No | The configuration target. You must set the target to `country` when specifying a country code in the rule. |
| `value` | string | No | The two-letter ISO-3166-1 alpha-2 code to match. For more information, refer to [IP Access rules: Parameters](https://developers.cloudflare.com/waf/tools/ip-access-rules/parameters/#country). |

