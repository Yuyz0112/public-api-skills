# POST /accounts/{account_id}/cloudforce-one/requests/{request_id}/message/new

**Resource:** [Request for Information (RFI)](../resources/Request-for-Information-RFI.md)
**Create a New Request Message**
**Operation ID:** `cloudforce-one-request-message-new`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | cloudforce-one-requests_identifier | Yes |  |
| `request_id` | path | cloudforce-one-requests_uuid | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [cloudforce-one-requests_request-message-edit](../schemas/cloudforce-one-requests/cloudforce-one-requests-request-message-edit.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Create request message response. |
| 4XX | Create request message response failure. |

## Security

- **api_email**
- **api_key**
