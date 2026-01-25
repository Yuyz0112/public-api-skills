# PATCH /zones/{zone_id}/firewall/waf/packages/{package_id}

**Resource:** [WAF packages](../resources/WAF-packages.md)
**Update a WAF package**
**Operation ID:** `waf-packages-update-a-waf-package`
⚠️ **Deprecated**

Updates a WAF package. You can update the sensitivity and the action of an anomaly detection WAF package.

**Note:** Applies only to the [previous version of WAF managed rules](https://developers.cloudflare.com/support/firewall/managed-rules-web-application-firewall-waf/understanding-waf-managed-rules-web-application-firewall/).

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `package_id` | path | firewall_package_id | Yes |  |
| `zone_id` | path | firewall_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Update a WAF package response |
| 4XX | Update a WAF package response failure |

## Security

- **api_email**
- **api_key**
- **api_token**
