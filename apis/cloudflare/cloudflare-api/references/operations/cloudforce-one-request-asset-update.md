# PUT /accounts/{account_id}/cloudforce-one/requests/{request_id}/asset/{asset_id}

**Resource:** [Request for Information (RFI)](../resources/Request-for-Information-RFI.md)
**Update a Request Asset**
**Operation ID:** `cloudforce-one-request-asset-update`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | cloudforce-one-requests_identifier | Yes |  |
| `request_id` | path | cloudforce-one-requests_uuid | Yes |  |
| `asset_id` | path | cloudforce-one-requests_uuid | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [cloudforce-one-requests_request-asset-edit](../schemas/cloudforce-one-requests/cloudforce-one-requests-request-asset-edit.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Update request asset response. |
| 4XX | Update request asset response failure. |

## Security

- **api_email**
- **api_key**
