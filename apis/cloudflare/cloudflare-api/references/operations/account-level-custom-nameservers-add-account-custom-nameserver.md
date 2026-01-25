# POST /accounts/{account_id}/custom_ns

**Resource:** [Account-Level Custom Nameservers](../resources/Account-Level-Custom-Nameservers.md)
**Add Account Custom Nameserver**
**Operation ID:** `account-level-custom-nameservers-add-account-custom-nameserver`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | dns-custom-nameservers_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [dns-custom-nameservers_CustomNSInput](../schemas/dns-custom-nameservers/dns-custom-nameservers-CustomNSInput.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Add Account Custom Nameserver response |
| 4XX | Add Account Custom Nameserver response failure |

**Success Response Schema:**

[dns-custom-nameservers_acns_response_single](../schemas/dns-custom-nameservers/dns-custom-nameservers-acns-response-single.md)

## Security

- **api_token**
- **api_email**
- **api_key**
