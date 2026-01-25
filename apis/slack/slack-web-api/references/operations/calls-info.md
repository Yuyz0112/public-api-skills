# GET /calls.info

**Resource:** [calls](../resources/calls.md)
**Operation ID:** `calls_info`

Returns information about a Call.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `token` | header | string | Yes | Authentication token. Requires scope: `calls:read` |
| `id` | query | string | Yes | `id` of the Call returned by the [`calls.add`](/methods/calls.add) method. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Typical success response |
| default | Typical error response |

## Security

- **slackAuth**: calls:read
