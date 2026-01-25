# GET /accounts/{account_id}/urlscanner/response/{response_id}

**Resource:** [URL Scanner (Deprecated)](../resources/URL-Scanner-Deprecated.md)
**Get raw response**
**Operation ID:** `urlscanner-get-response-text`
⚠️ **Deprecated**

Returns the plain response of the network request.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `response_id` | path | string | Yes | Response hash. |
| `account_id` | path | string | Yes | Account ID. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | When `har.log.entries[].response._cf.contentAvailable` is `true`, use `response._cf.hash` value to fetch the raw response. |
| 400 | Invalid params. |
| 404 | Scan not found. |

## Security

- **api_token**
- **api_email**
- **api_key**
