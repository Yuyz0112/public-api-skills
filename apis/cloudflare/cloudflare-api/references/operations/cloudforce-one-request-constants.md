# GET /accounts/{account_id}/cloudforce-one/requests/constants

**Resource:** [Request for Information (RFI)](../resources/Request-for-Information-RFI.md)
**Get Request Priority, Status, and TLP constants**
**Operation ID:** `cloudforce-one-request-constants`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | cloudforce-one-requests_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Get request constants response. |
| 4XX | Get request constants response failure. |

## Security

- **api_email**
- **api_key**
