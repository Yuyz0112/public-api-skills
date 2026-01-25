# GET /accounts/{account_id}/custom_ns

**Resource:** [Account-Level Custom Nameservers](../resources/Account-Level-Custom-Nameservers.md)
**List Account Custom Nameservers**
**Operation ID:** `account-level-custom-nameservers-list-account-custom-nameservers`

List an account's custom nameservers.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | dns-custom-nameservers_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | List Account Custom Nameservers response |
| 4XX | List Account Custom Nameservers response failure |

**Success Response Schema:**

[dns-custom-nameservers_acns_response_collection](../schemas/dns-custom-nameservers/dns-custom-nameservers-acns-response-collection.md)

## Security

- **api_token**
- **api_email**
- **api_key**
