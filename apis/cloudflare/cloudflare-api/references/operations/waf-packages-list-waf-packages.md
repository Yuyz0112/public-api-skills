# GET /zones/{zone_id}/firewall/waf/packages

**Resource:** [WAF packages](../resources/WAF-packages.md)
**List WAF packages**
**Operation ID:** `waf-packages-list-waf-packages`
⚠️ **Deprecated**

Fetches WAF packages for a zone.

**Note:** Applies only to the [previous version of WAF managed rules](https://developers.cloudflare.com/support/firewall/managed-rules-web-application-firewall-waf/understanding-waf-managed-rules-web-application-firewall/).

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `zone_id` | path | firewall_identifier | Yes |  |
| `page` | query | number | No |  |
| `per_page` | query | number | No |  |
| `order` | query | enum: name | No |  |
| `direction` | query | enum: asc, desc | No |  |
| `match` | query | enum: any, all | No |  |
| `name` | query | string | No |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | List WAF packages response |
| 4XX | List WAF packages response failure |

**Success Response Schema:**

[firewall_package_response_collection](../schemas/firewall/firewall-package-response-collection.md)

## Security

- **api_email**
- **api_key**
- **api_token**
