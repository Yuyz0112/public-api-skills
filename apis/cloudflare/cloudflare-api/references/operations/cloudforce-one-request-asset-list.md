# POST /accounts/{account_id}/cloudforce-one/requests/{request_id}/asset

**Resource:** [Request for Information (RFI)](../resources/Request-for-Information-RFI.md)
**List Request Assets**
**Operation ID:** `cloudforce-one-request-asset-list`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | cloudforce-one-requests_identifier | Yes |  |
| `request_id` | path | cloudforce-one-requests_uuid | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [cloudforce-one-requests_request-asset-list](../schemas/cloudforce-one-requests/cloudforce-one-requests-request-asset-list.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | List request assets response. |
| 4XX | List request assets response failure. |

## Security

- **api_email**
- **api_key**
