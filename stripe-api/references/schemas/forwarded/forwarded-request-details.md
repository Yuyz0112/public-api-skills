# forwarded_request_details

Details about the request forwarded to the destination endpoint.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `body` | string | Yes | The body payload to send to the destination endpoint. |
| `headers` | forwarded_request_header[] | Yes | The headers to include in the forwarded request. Can be omitted if no additional headers (excluding Stripe-generated ones such as the Content-Type header) should be included. |
| `http_method` | enum: POST | Yes | The HTTP method used to call the destination endpoint. |

