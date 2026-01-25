# GET /accounts/{account_id}/cloudforce-one/requests/{request_id}

**Resource:** [Request for Information (RFI)](../resources/Request-for-Information-RFI.md)
**Get a Request**
**Operation ID:** `cloudforce-one-request-get`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | cloudforce-one-requests_identifier | Yes |  |
| `request_id` | path | cloudforce-one-requests_uuid | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Get request response. |
| 4XX | Get request response failure. |

## Security

- **api_email**
- **api_key**
