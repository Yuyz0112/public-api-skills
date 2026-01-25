# repository-advisory-create

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `summary` | string | Yes | A short summary of the advisory. |
| `description` | string | Yes | A detailed description of what the advisory impacts. |
| `cve_id` | string | No | The Common Vulnerabilities and Exposures (CVE) ID. |
| `vulnerabilities` | object[] | Yes | A product affected by the vulnerability detailed in a repository security advisory. |
| `cwe_ids` | string[] | No | A list of Common Weakness Enumeration (CWE) IDs. |
| `credits` | object[] | No | A list of users receiving credit for their participation in the security advisory. |
| `severity` | enum: critical, high, medium... | No | The severity of the advisory. You must choose between setting this field or `cvss_vector_string`. |
| `cvss_vector_string` | string | No | The CVSS vector that calculates the severity of the advisory. You must choose between setting this field or `severity`. |
| `start_private_fork` | boolean | No | Whether to create a temporary private fork of the repository to collaborate on a fix. |

## Nested Fields

### `vulnerabilities`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `package` | object | Yes | The name of the package affected by the vulnerability. |
| `vulnerable_version_range` | string | No | The range of the package versions affected by the vulnerability. |
| `patched_versions` | string | No | The package version(s) that resolve the vulnerability. |
| `vulnerable_functions` | string[] | No | The functions in the package that are affected. |

#### `vulnerabilities.package`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `ecosystem` | [security-advisory-ecosystems](security-advisory-ecosystems.md) | Yes |  |
| `name` | string | No | The unique package name within its ecosystem. |

### `credits`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `login` | string | Yes | The username of the user credited. |
| `type` | [security-advisory-credit-types](security-advisory-credit-types.md) | Yes |  |

