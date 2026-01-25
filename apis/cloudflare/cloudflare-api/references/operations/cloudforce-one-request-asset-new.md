# POST /accounts/{account_id}/cloudforce-one/requests/{request_id}/asset/new

**Resource:** [Request for Information (RFI)](../resources/Request-for-Information-RFI.md)
**Create a New Request Asset**
**Operation ID:** `cloudforce-one-request-asset-new`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | cloudforce-one-requests_identifier | Yes |  |
| `request_id` | path | cloudforce-one-requests_uuid | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `multipart/form-data`

**Schema:** [cloudforce-one-requests_request-asset-edit](../schemas/cloudforce-one-requests/cloudforce-one-requests-request-asset-edit.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Create request asset response. |
| 4XX | Create request asset response failure. |

## Security

- **api_email**
- **api_key**
