# GET /accounts/{account_id}/cni/interconnects/{icon}/status

**Resource:** [Interconnects](../resources/Interconnects.md)
**Get the current status of an interconnect object**
**Operation ID:** `get_interconnect_status`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `icon` | path | string | Yes | Interconnect name to retrieve information about |
| `account_id` | path | nsc_AccountTag | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Current interconnect status |
| 400 | Bad request |
| 404 | Interconnect not found |
| 500 | Internal server error |

**Success Response Schema:**

[nsc_StatusInfo](../schemas/nsc/nsc-StatusInfo.md)

## Security

- **api_email**
- **api_key**
- **api_token**
