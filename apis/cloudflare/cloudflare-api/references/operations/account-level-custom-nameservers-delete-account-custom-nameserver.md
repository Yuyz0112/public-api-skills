# DELETE /accounts/{account_id}/custom_ns/{custom_ns_id}

**Resource:** [Account-Level Custom Nameservers](../resources/Account-Level-Custom-Nameservers.md)
**Delete Account Custom Nameserver**
**Operation ID:** `account-level-custom-nameservers-delete-account-custom-nameserver`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `custom_ns_id` | path | dns-custom-nameservers_ns_name | Yes |  |
| `account_id` | path | dns-custom-nameservers_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Delete Account Custom Nameserver response |
| 4XX | Delete Account Custom Nameserver response failure |

**Success Response Schema:**

[dns-custom-nameservers_empty_response](../schemas/dns-custom-nameservers/dns-custom-nameservers-empty-response.md)

## Security

- **api_token**
- **api_email**
- **api_key**
