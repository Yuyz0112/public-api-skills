# PATCH /accounts/{account_id}/dns_settings/views/{view_id}

**Resource:** [DNS Internal Views for an Account](../resources/DNS-Internal-Views-for-an-Account.md)
**Update Internal DNS View**
**Operation ID:** `dns-views-for-an-account-update-internal-dns-view`

Update an existing Internal DNS View

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | dns-settings_identifier | Yes |  |
| `view_id` | path | dns-settings_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [dns-settings_dns-view-patch](../schemas/dns-settings/dns-settings-dns-view-patch.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Update Internal DNS View response |
| 4XX | Update Internal DNS View response failure |

**Success Response Schema:**

[dns-settings_dns_view_response_single](../schemas/dns-settings/dns-settings-dns-view-response-single.md)

## Security

- **api_token**
- **api_email**
- **api_key**
