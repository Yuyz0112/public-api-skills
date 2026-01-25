# GET /accounts/{account_id}/cloudforce-one/requests/{request_id}/asset/{asset_id}

**Resource:** [Request for Information (RFI)](../resources/Request-for-Information-RFI.md)
**Get a Request Asset**
**Operation ID:** `cloudforce-one-request-asset-get`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | cloudforce-one-requests_identifier | Yes |  |
| `request_id` | path | cloudforce-one-requests_uuid | Yes |  |
| `asset_id` | path | cloudforce-one-requests_uuid | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Get request asset response. |
| 4XX | Get request asset response failure. |

## Security

- **api_email**
- **api_key**
