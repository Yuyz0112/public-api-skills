# GET /accounts/{account_id}/cloudforce-one/scans/config

**Resource:** [Scans](../resources/Scans.md)
**List Scan Configs**
**Operation ID:** `get_ConfigFetch`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | string | Yes | Defines the Account ID. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returns all Scan Configs. |
| 4XX | List Scan Configs failure. |

## Security

- **api_token**
- **api_email**
- **api_key**
