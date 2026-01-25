# GET /accounts/{account_id}/intel/ip-list

**Resource:** [IP List](../resources/IP-List.md)
**Get IP Lists**
**Operation ID:** `ip-list-get-ip-lists`

Get IP Lists.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | intel_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Get IP Lists response. |
| 4XX | Get IP Lists response failure. |

**Success Response Schema:**

[intel_components-schemas-response](../schemas/intel/intel-components-schemas-response.md)

## Security

- **api_token**
- **api_email**
- **api_key**
