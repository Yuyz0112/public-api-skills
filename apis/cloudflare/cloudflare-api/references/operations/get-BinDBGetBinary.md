# GET /accounts/{account_id}/cloudforce-one/binary/{hash}

**Resource:** [BinDB](../resources/BinDB.md)
**Retrieves a file from Binary Storage**
**Operation ID:** `get_BinDBGetBinary`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | number | Yes | Account ID. |
| `hash` | path | string | Yes | hash of the binary |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returns file information |
| 400 | Bad Request. |

## Security

- **api_token**
