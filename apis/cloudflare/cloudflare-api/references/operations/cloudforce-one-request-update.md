# PUT /accounts/{account_id}/cloudforce-one/requests/{request_id}

**Resource:** [Request for Information (RFI)](../resources/Request-for-Information-RFI.md)
**Update a Request**
**Operation ID:** `cloudforce-one-request-update`

Updating a request alters the request in the Cloudforce One queue. This API may be used to update any attributes of the request after the initial submission. Only fields that you choose to update need to be add to the request body.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | cloudforce-one-requests_identifier | Yes |  |
| `request_id` | path | cloudforce-one-requests_uuid | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [cloudforce-one-requests_request-edit](../schemas/cloudforce-one-requests/cloudforce-one-requests-request-edit.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Update request response. |
| 4XX | Update request response failure. |

## Security

- **api_email**
- **api_key**
