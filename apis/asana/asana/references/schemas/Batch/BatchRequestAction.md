# BatchRequestAction

An action object for use in a batch request.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `relative_path` | string | Yes | The path of the desired endpoint relative to the API’s base URL. Query parameters are not accepted here; put them in `data` instead. |
| `method` | enum: get, post, put... | Yes | The HTTP method you wish to emulate for the action. |
| `data` | object | No | For `GET` requests, this should be a map of query parameters you would have normally passed in the URL. Options and pagination are not accepted here; put them in `options` instead. For `POST`, `PATCH`, and `PUT` methods, this should be the content you would have normally put in the data field of the body. |
| `options` | object | No | Pagination (`limit` and `offset`) and output options (`fields` or `expand`) for the action. “Pretty” JSON output is not an available option on individual actions; if you want pretty output, specify that option on the parent request. |

## Nested Fields

### `options`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `limit` | integer | No | Pagination limit for the request. |
| `offset` | integer | No | Pagination offset for the request. |
| `fields` | string[] | No | The fields to retrieve in the request. |

