# package

A software package

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | integer | Yes | Unique identifier of the package. |
| `name` | string | Yes | The name of the package. |
| `package_type` | enum: npm, maven, rubygems... | Yes |  |
| `url` | string | Yes |  |
| `html_url` | string | Yes |  |
| `version_count` | integer | Yes | The number of versions of the package. |
| `visibility` | enum: private, public | Yes |  |
| `owner` | [nullable-simple-user](nullable-simple-user.md) | No |  |
| `repository` | [nullable-minimal-repository](nullable-minimal-repository.md) | No |  |
| `created_at` | string (date-time) | Yes |  |
| `updated_at` | string (date-time) | Yes |  |

