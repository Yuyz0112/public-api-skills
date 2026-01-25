# GET /accounts/{account_id}/intel/whois

**Resource:** [WHOIS Record](../resources/WHOIS-Record.md)
**Get WHOIS Record**
**Operation ID:** `whois-record-get-whois-record`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | cloudforce-one-whois_identifier | Yes |  |
| `domain` | query | string | No |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Get WHOIS Record response. |
| 4XX | Get WHOIS Record response failure. |

**Success Response Schema:**

[cloudforce-one-whois_schemas-single_response](../schemas/cloudforce-one-whois/cloudforce-one-whois-schemas-single-response.md)

## Security

- **api_token**
- **api_email**
- **api_key**
