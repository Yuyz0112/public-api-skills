# GET /accounts/{account_id}/cni/interconnects/{icon}

**Resource:** [Interconnects](../resources/Interconnects.md)
**Get information about an interconnect object**
**Operation ID:** `get_interconnect`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `icon` | path | string | Yes | Interconnect name to retrieve information about |
| `account_id` | path | nsc_AccountTag | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Information about the specified interconnect |
| 400 | Bad request |
| 404 | Interconnect not found |
| 500 | Internal server error |

**Success Response Schema:**

[nsc_Interconnect](../schemas/nsc/nsc-Interconnect.md)

## Security

- **api_email**
- **api_key**
- **api_token**
