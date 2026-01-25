# DELETE /accounts/{account_id}/cloudforce-one/scans/config/{config_id}

**Resource:** [Scans](../resources/Scans.md)
**Delete a Scan Config**
**Operation ID:** `delete_DeleteScans`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | string | Yes | Defines the Account ID. |
| `config_id` | path | string | Yes | Defines the Config ID. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Delete a Scan Config. |
| 4XX | Delete a Scan Config failure. |

## Security

- **api_token**
- **api_email**
- **api_key**
