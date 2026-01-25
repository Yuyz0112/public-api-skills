# POST /accounts/{account_id}/cloudforce-one/requests/new

**Resource:** [Request for Information (RFI)](../resources/Request-for-Information-RFI.md)
**Create a New Request.**
**Operation ID:** `cloudforce-one-request-new`

Creating a request adds the request into the Cloudforce One queue for analysis. In addition to the content, a short title, type, priority, and releasability should be provided. If one is not provided, a default will be assigned.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | cloudforce-one-requests_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [cloudforce-one-requests_request-edit](../schemas/cloudforce-one-requests/cloudforce-one-requests-request-edit.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Create request response. |
| 4XX | Create response failure. |

## Security

- **api_email**
- **api_key**
