# aaa_schemas-api-response-common-failure

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `errors` | object[] | Yes | A list of error messages. |
| `messages` | object[] | No |  |
| `success` | enum: false | Yes | Indicates whether the API call was failed |

## Nested Fields

### `errors`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `message` | string | Yes | A text description of this message. |

### `messages`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `message` | string | No |  |

