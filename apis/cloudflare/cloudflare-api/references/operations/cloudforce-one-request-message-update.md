# PUT /accounts/{account_id}/cloudforce-one/requests/{request_id}/message/{message_id}

**Resource:** [Request for Information (RFI)](../resources/Request-for-Information-RFI.md)
**Update a Request Message**
**Operation ID:** `cloudforce-one-request-message-update`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | cloudforce-one-requests_identifier | Yes |  |
| `request_id` | path | cloudforce-one-requests_uuid | Yes |  |
| `message_id` | path | integer | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [cloudforce-one-requests_request-message-edit](../schemas/cloudforce-one-requests/cloudforce-one-requests-request-message-edit.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Update request message response. |
| 4XX | Update request message response failure. |

## Security

- **api_email**
- **api_key**
