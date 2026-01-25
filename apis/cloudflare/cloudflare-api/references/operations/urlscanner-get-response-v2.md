# GET /accounts/{account_id}/urlscanner/v2/responses/{response_id}

**Resource:** [URL Scanner](../resources/URL-Scanner.md)
**Get raw response**
**Operation ID:** `urlscanner-get-response-v2`

Returns the raw response of the network request. Find the `response_id` in the `data.requests.response.hash`.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `response_id` | path | string | Yes | Response hash. |
| `account_id` | path | string | Yes | Account ID. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Get the raw response by its hash. |
| 400 | Invalid input. |

## Security

- **api_token**
- **api_email**
- **api_key**
