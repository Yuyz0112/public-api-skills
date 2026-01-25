# GET /api.test

**Resource:** [api](../resources/api.md)
**Operation ID:** `api_test`

Checks API calling code.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `error` | query | string | No | Error response to return |
| `foo` | query | string | No | example property to return |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Standard success response |
| default | Artificial error response |

## Security

- **slackAuth**: none
