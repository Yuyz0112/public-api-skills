# global-advisory

A GitHub Security Advisory.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `ghsa_id` | string | Yes | The GitHub Security Advisory ID. |
| `cve_id` | string | Yes | The Common Vulnerabilities and Exposures (CVE) ID. |
| `url` | string | Yes | The API URL for the advisory. |
| `html_url` | string (uri) | Yes | The URL for the advisory. |
| `repository_advisory_url` | string (uri) | Yes | The API URL for the repository advisory. |
| `summary` | string | Yes | A short summary of the advisory. |
| `description` | string | Yes | A detailed description of what the advisory entails. |
| `type` | enum: reviewed, unreviewed, malware | Yes | The type of advisory. |
| `severity` | enum: critical, high, medium... | Yes | The severity of the advisory. |
| `source_code_location` | string (uri) | Yes | The URL of the advisory's source code. |
| `identifiers` | object[] | Yes |  |
| `references` | string[] | Yes |  |
| `published_at` | string (date-time) | Yes | The date and time of when the advisory was published, in ISO 8601 format. |
| `updated_at` | string (date-time) | Yes | The date and time of when the advisory was last updated, in ISO 8601 format. |
| `github_reviewed_at` | string (date-time) | Yes | The date and time of when the advisory was reviewed by GitHub, in ISO 8601 format. |
| `nvd_published_at` | string (date-time) | Yes | The date and time when the advisory was published in the National Vulnerability Database, in ISO 8601 format.
This field is only populated when the advisory is imported from the National Vulnerability Database. |
| `withdrawn_at` | string (date-time) | Yes | The date and time of when the advisory was withdrawn, in ISO 8601 format. |
| `vulnerabilities` | vulnerability[] | Yes | The products and respective version ranges affected by the advisory. |
| `cvss` | object | Yes |  |
| `cvss_severities` | [cvss-severities](cvss-severities.md) | No |  |
| `epss` | [security-advisory-epss](security-advisory-epss.md) | No |  |
| `cwes` | object[] | Yes |  |
| `credits` | object[] | Yes | The users who contributed to the advisory. |

## Nested Fields

### `identifiers`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `type` | enum: CVE, GHSA | Yes | The type of identifier. |
| `value` | string | Yes | The identifier value. |

### `cvss`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `vector_string` | string | Yes | The CVSS vector. |
| `score` | number | Yes | The CVSS score. |

### `cwes`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `cwe_id` | string | Yes | The Common Weakness Enumeration (CWE) identifier. |
| `name` | string | Yes | The name of the CWE. |

### `credits`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `user` | [simple-user](simple-user.md) | Yes |  |
| `type` | [security-advisory-credit-types](security-advisory-credit-types.md) | Yes |  |

