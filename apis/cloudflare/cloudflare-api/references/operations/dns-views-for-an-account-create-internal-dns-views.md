# POST /accounts/{account_id}/dns_settings/views

**Resource:** [DNS Internal Views for an Account](../resources/DNS-Internal-Views-for-an-Account.md)
**Create Internal DNS View**
**Operation ID:** `dns-views-for-an-account-create-internal-dns-views`

Create Internal DNS View for an account

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | dns-settings_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [dns-settings_dns-view-post](../schemas/dns-settings/dns-settings-dns-view-post.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Create Internal DNS View response |
| 4XX | Create Internal DNS View response failure |

**Success Response Schema:**

[dns-settings_dns_view_response_single](../schemas/dns-settings/dns-settings-dns-view-response-single.md)

## Security

- **api_token**
- **api_email**
- **api_key**
