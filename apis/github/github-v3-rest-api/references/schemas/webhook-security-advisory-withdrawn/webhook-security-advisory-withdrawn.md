# webhook-security-advisory-withdrawn

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `action` | enum: withdrawn | Yes |  |
| `enterprise` | [enterprise-webhooks](enterprise-webhooks.md) | No |  |
| `installation` | [simple-installation](simple-installation.md) | No |  |
| `organization` | [organization-simple-webhooks](organization-simple-webhooks.md) | No |  |
| `repository` | [repository-webhooks](repository-webhooks.md) | No |  |
| `security_advisory` | object | Yes | The details of the security advisory, including summary, description, and severity. |
| `sender` | [simple-user](simple-user.md) | No |  |

## Nested Fields

### `security_advisory`

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

#### `security_advisory.cvss`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `score` | number | Yes |  |
| `vector_string` | string | Yes |  |

#### `security_advisory.cwes`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `cwe_id` | string | Yes |  |
| `name` | string | Yes |  |

#### `security_advisory.identifiers`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `type` | string | Yes |  |
| `value` | string | Yes |  |

#### `security_advisory.references`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `url` | string (uri) | Yes |  |

#### `security_advisory.vulnerabilities`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `first_patched_version` | object | Yes |  |
| `package` | object | Yes |  |
| `severity` | string | Yes |  |
| `vulnerable_version_range` | string | Yes |  |

