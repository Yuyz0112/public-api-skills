# api-shield_schema_issue_notification

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `code` | integer | Yes | A unique error code that describes the kind of issue with the schema |
| `message` | string | Yes | A short text explaining the issue with the schema |
| `source` | object | No |  |

## Nested Fields

### `source`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `locations` | string[] | No | A list of JSON path expression(s) that describe the location(s) of the issue within the provided resource. See [https://goessner.net/articles/JsonPath/](https://goessner.net/articles/JsonPath/) for JSONPath specification. |

