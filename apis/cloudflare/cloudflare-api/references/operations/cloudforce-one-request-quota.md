# GET /accounts/{account_id}/cloudforce-one/requests/quota

**Resource:** [Request for Information (RFI)](../resources/Request-for-Information-RFI.md)
**Get Request Quota**
**Operation ID:** `cloudforce-one-request-quota`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | cloudforce-one-requests_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Get request quota response. |
| 4XX | Get request quota response failure. |

## Security

- **api_email**
- **api_key**
