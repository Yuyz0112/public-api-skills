# GET /accounts/{account_id}/cloudforce-one/requests/types

**Resource:** [Request for Information (RFI)](../resources/Request-for-Information-RFI.md)
**Get Request Types**
**Operation ID:** `cloudforce-one-request-types`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | cloudforce-one-requests_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Get request types response. |
| 4XX | Get request types response failure. |

## Security

- **api_email**
- **api_key**
