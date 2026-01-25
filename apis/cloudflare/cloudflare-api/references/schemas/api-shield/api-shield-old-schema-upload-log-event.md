# api-shield_old_schema_upload_log_event

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `code` | integer | Yes | Code that identifies the event that occurred. |
| `locations` | string[] | No | JSONPath location(s) in the schema where these events were encountered.  See [https://goessner.net/articles/JsonPath/](https://goessner.net/articles/JsonPath/) for JSONPath specification. |
| `message` | string | No | Diagnostic message that describes the event. |

