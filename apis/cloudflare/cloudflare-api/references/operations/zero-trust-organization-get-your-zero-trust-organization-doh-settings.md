# GET /accounts/{account_id}/access/organizations/doh

**Resource:** [Zero Trust organization](../resources/Zero-Trust-organization.md)
**Get your Zero Trust organization DoH settings**
**Operation ID:** `zero-trust-organization-get-your-zero-trust-organization-doh-settings`

Returns the DoH settings for your Zero Trust organization.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | access_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Get your Zero Trust organization DoH settings response |
| 4XX | Get your Zero Trust organization DoH settings response failure |

## Security

- **api_email**
- **api_key**
- **api_token**
