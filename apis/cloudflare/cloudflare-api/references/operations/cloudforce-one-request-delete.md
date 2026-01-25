# DELETE /accounts/{account_id}/cloudforce-one/requests/{request_id}

**Resource:** [Request for Information (RFI)](../resources/Request-for-Information-RFI.md)
**Delete a Request**
**Operation ID:** `cloudforce-one-request-delete`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | cloudforce-one-requests_identifier | Yes |  |
| `request_id` | path | cloudforce-one-requests_uuid | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Delete request response. |
| 4XX | Delete request response failure. |

**Success Response Schema:**

[cloudforce-one-requests_api-response-common](../schemas/cloudforce-one-requests/cloudforce-one-requests-api-response-common.md)

## Security

- **api_email**
- **api_key**
