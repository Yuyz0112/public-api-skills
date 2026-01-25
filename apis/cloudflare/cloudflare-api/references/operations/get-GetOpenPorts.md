# GET /accounts/{account_id}/cloudforce-one/scans/results/{config_id}

**Resource:** [Scans](../resources/Scans.md)
**Get the Latest Scan Result**
**Operation ID:** `get_GetOpenPorts`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | string | Yes | Defines the Account ID. |
| `config_id` | path | string | Yes | Defines the Config ID. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returns Current Open Ports. |
| 4XX | Get the Latest Scan Result failure. |

## Security

- **api_token**
- **api_email**
- **api_key**
