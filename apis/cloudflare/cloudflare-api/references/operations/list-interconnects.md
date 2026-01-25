# GET /accounts/{account_id}/cni/interconnects

**Resource:** [Interconnects](../resources/Interconnects.md)
**List existing interconnects**
**Operation ID:** `list_interconnects`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `site` | query | string | No | If specified, only show interconnects located at the given site |
| `type` | query | string | No | If specified, only show interconnects of the given type |
| `cursor` | query | integer (int32) | No |  |
| `limit` | query | integer | No |  |
| `account_id` | path | nsc_AccountTag | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | List of matching interconnect objects |
| 400 | Bad request |
| 500 | Internal server error |

**Success Response Schema:**

[nsc_InterconnectList](../schemas/nsc/nsc-InterconnectList.md)

## Security

- **api_email**
- **api_key**
- **api_token**
