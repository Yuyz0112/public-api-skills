# GET /accounts/{account_id}/dns_settings/views/{view_id}

**Resource:** [DNS Internal Views for an Account](../resources/DNS-Internal-Views-for-an-Account.md)
**DNS Internal View Details**
**Operation ID:** `dns-views-for-an-account-get-internal-dns-view`

Get DNS Internal View

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | dns-settings_identifier | Yes |  |
| `view_id` | path | dns-settings_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Get DNS Internal View response |
| 4XX | List Internal DNS Views response failure |

**Success Response Schema:**

[dns-settings_dns_view_response_single](../schemas/dns-settings/dns-settings-dns-view-response-single.md)

## Security

- **api_token**
- **api_email**
- **api_key**
