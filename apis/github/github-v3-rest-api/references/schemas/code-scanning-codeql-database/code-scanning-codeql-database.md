# code-scanning-codeql-database

A CodeQL database.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | integer | Yes | The ID of the CodeQL database. |
| `name` | string | Yes | The name of the CodeQL database. |
| `language` | string | Yes | The language of the CodeQL database. |
| `uploader` | [simple-user](simple-user.md) | Yes |  |
| `content_type` | string | Yes | The MIME type of the CodeQL database file. |
| `size` | integer | Yes | The size of the CodeQL database file in bytes. |
| `created_at` | string (date-time) | Yes | The date and time at which the CodeQL database was created, in ISO 8601 format':' YYYY-MM-DDTHH:MM:SSZ. |
| `updated_at` | string (date-time) | Yes | The date and time at which the CodeQL database was last updated, in ISO 8601 format':' YYYY-MM-DDTHH:MM:SSZ. |
| `url` | string (uri) | Yes | The URL at which to download the CodeQL database. The `Accept` header must be set to the value of the `content_type` property. |
| `commit_oid` | string | No | The commit SHA of the repository at the time the CodeQL database was created. |

