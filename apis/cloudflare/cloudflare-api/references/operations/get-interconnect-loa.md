# GET /accounts/{account_id}/cni/interconnects/{icon}/loa

**Resource:** [Interconnects](../resources/Interconnects.md)
**Generate the Letter of Authorization (LOA) for a given interconnect**
**Operation ID:** `get_interconnect_loa`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `icon` | path | string | Yes | Interconnect name to retrieve information about |
| `account_id` | path | nsc_AccountTag | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Generated LOA in PDF format |
| 400 | Bad request |
| 404 | Interconnect not found |
| 500 | Internal server error |

## Security

- **api_email**
- **api_key**
- **api_token**
