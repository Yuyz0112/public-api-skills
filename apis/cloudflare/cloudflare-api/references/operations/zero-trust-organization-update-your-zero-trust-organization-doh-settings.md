# PUT /accounts/{account_id}/access/organizations/doh

**Resource:** [Zero Trust organization](../resources/Zero-Trust-organization.md)
**Update your Zero Trust organization DoH settings**
**Operation ID:** `zero-trust-organization-update-your-zero-trust-organization-doh-settings`

Updates the DoH settings for your Zero Trust organization.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | access_identifier | Yes |  |

## Request Body

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 201 | Update your Zero Trust organization DoH settings response |
| 4XX | Update your Zero Trust organization DoH settings response failure |

## Security

- **api_email**
- **api_key**
- **api_token**
