# GET /accounts/{account_id}/cni/cnis

**Resource:** [CNIs](../resources/CNIs.md)
**List existing CNI objects**
**Operation ID:** `list_cnis`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `slot` | query | string | No | If specified, only show CNIs associated with the specified slot |
| `tunnel_id` | query | string | No | If specified, only show cnis associated with the specified tunnel id |
| `cursor` | query | integer (int32) | No |  |
| `limit` | query | integer | No |  |
| `account_id` | path | nsc_AccountTag | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | List of matching CNI objects |
| 400 | Bad request |
| 500 | Internal server error |

**Success Response Schema:**

[nsc_CniList](../schemas/nsc/nsc-CniList.md)

## Security

- **api_email**
- **api_key**
- **api_token**
