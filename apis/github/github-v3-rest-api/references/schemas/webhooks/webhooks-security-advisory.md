# webhooks_security_advisory

The details of the security advisory, including summary, description, and severity.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `cvss` | object | Yes |  |
| `cvss_severities` | [cvss-severities](cvss-severities.md) | No |  |
| `cwes` | object[] | Yes |  |
| `description` | string | Yes |  |
| `ghsa_id` | string | Yes |  |
| `identifiers` | object[] | Yes |  |
| `published_at` | string | Yes |  |
| `references` | object[] | Yes |  |
| `severity` | string | Yes |  |
| `summary` | string | Yes |  |
| `updated_at` | string | Yes |  |
| `vulnerabilities` | object[] | Yes |  |
| `withdrawn_at` | string | Yes |  |

## Nested Fields

### `cvss`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `score` | number | Yes |  |
| `vector_string` | string | Yes |  |

### `cwes`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `cwe_id` | string | Yes |  |
| `name` | string | Yes |  |

### `identifiers`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `type` | string | Yes |  |
| `value` | string | Yes |  |

### `references`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `url` | string (uri) | Yes |  |

### `vulnerabilities`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `first_patched_version` | object | Yes |  |
| `package` | object | Yes |  |
| `severity` | string | Yes |  |
| `vulnerable_version_range` | string | Yes |  |

#### `vulnerabilities.first_patched_version`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `identifier` | string | Yes |  |

#### `vulnerabilities.package`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `ecosystem` | string | Yes |  |
| `name` | string | Yes |  |

