# DELETE /accounts/{account_id}/dns_settings/views/{view_id}

**Resource:** [DNS Internal Views for an Account](../resources/DNS-Internal-Views-for-an-Account.md)
**Delete Internal DNS View**
**Operation ID:** `dns-views-for-an-account-delete-internal-dns-view`

Delete an existing Internal DNS View

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | dns-settings_identifier | Yes |  |
| `view_id` | path | dns-settings_identifier | Yes |  |

## Request Body

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Delete Internal DNS View response |
| 4XX | Update Internal DNS View response failure |

## Security

- **api_token**
- **api_email**
- **api_key**
