# GET /zones/{zone_id}/firewall/waf/packages/{package_id}

**Resource:** [WAF packages](../resources/WAF-packages.md)
**Get a WAF package**
**Operation ID:** `waf-packages-get-a-waf-package`
⚠️ **Deprecated**

Fetches the details of a WAF package.

**Note:** Applies only to the [previous version of WAF managed rules](https://developers.cloudflare.com/support/firewall/managed-rules-web-application-firewall-waf/understanding-waf-managed-rules-web-application-firewall/).

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `package_id` | path | firewall_package_id | Yes |  |
| `zone_id` | path | firewall_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Get a WAF package response |
| 4XX | Get a WAF package response failure |

**Success Response Schema:**

[firewall_package_response_single](../schemas/firewall/firewall-package-response-single.md)

## Security

- **api_email**
- **api_key**
- **api_token**
