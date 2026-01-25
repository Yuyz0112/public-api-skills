# BatchResponse

A response object returned from a batch request.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `status_code` | integer | No | The HTTP status code that the invoked endpoint returned. |
| `headers` | object | No | A map of HTTP headers specific to this result. This is primarily used for returning a `Location` header to accompany a `201 Created` result.  The parent HTTP response will contain all common headers. |
| `body` | object | No | The JSON body that the invoked endpoint returned. |

