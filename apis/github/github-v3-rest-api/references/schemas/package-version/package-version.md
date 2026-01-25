# package-version

A version of a software package

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | integer | Yes | Unique identifier of the package version. |
| `name` | string | Yes | The name of the package version. |
| `url` | string | Yes |  |
| `package_html_url` | string | Yes |  |
| `html_url` | string | No |  |
| `license` | string | No |  |
| `description` | string | No |  |
| `created_at` | string (date-time) | Yes |  |
| `updated_at` | string (date-time) | Yes |  |
| `deleted_at` | string (date-time) | No |  |
| `metadata` | object | No |  |

## Nested Fields

### `metadata`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `package_type` | enum: npm, maven, rubygems... | Yes |  |
| `container` | object | No |  |
| `docker` | object | No |  |

#### `metadata.container`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `tags` | string[] | Yes |  |

#### `metadata.docker`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `tag` | string[] | No |  |

