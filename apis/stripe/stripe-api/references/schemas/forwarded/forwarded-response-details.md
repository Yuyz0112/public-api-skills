# forwarded_response_details

Details about the response from the destination endpoint.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `body` | string | Yes | The response body from the destination endpoint to Stripe. |
| `headers` | forwarded_request_header[] | Yes | HTTP headers that the destination endpoint returned. |
| `status` | integer | Yes | The HTTP status code that the destination endpoint returned. |

