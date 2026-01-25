# POST /accounts/{account_id}/cloudforce-one/requests/{request_id}/message

**Resource:** [Request for Information (RFI)](../resources/Request-for-Information-RFI.md)
**List Request Messages**
**Operation ID:** `cloudforce-one-request-message-list`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | cloudforce-one-requests_identifier | Yes |  |
| `request_id` | path | cloudforce-one-requests_uuid | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [cloudforce-one-requests_request-message-list](../schemas/cloudforce-one-requests/cloudforce-one-requests-request-message-list.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | List request messages response. |
| 4XX | List request messages response failure. |

## Security

- **api_email**
- **api_key**
