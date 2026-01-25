# repository-advisory

A repository security advisory.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `ghsa_id` | string | Yes | The GitHub Security Advisory ID. |
| `cve_id` | string | Yes | The Common Vulnerabilities and Exposures (CVE) ID. |
| `url` | string (uri) | Yes | The API URL for the advisory. |
| `html_url` | string (uri) | Yes | The URL for the advisory. |
| `summary` | string | Yes | A short summary of the advisory. |
| `description` | string | Yes | A detailed description of what the advisory entails. |
| `severity` | enum: critical, high, medium... | Yes | The severity of the advisory. |
| `author` | any | Yes | The author of the advisory. |
| `publisher` | any | Yes | The publisher of the advisory. |
| `identifiers` | object[] | Yes |  |
| `state` | enum: published, closed, withdrawn... | Yes | The state of the advisory. |
| `created_at` | string (date-time) | Yes | The date and time of when the advisory was created, in ISO 8601 format. |
| `updated_at` | string (date-time) | Yes | The date and time of when the advisory was last updated, in ISO 8601 format. |
| `published_at` | string (date-time) | Yes | The date and time of when the advisory was published, in ISO 8601 format. |
| `closed_at` | string (date-time) | Yes | The date and time of when the advisory was closed, in ISO 8601 format. |
| `withdrawn_at` | string (date-time) | Yes | The date and time of when the advisory was withdrawn, in ISO 8601 format. |
| `submission` | object | Yes |  |
| `vulnerabilities` | repository-advisory-vulnerability[] | Yes |  |
| `cvss` | object | Yes |  |
| `cvss_severities` | [cvss-severities](cvss-severities.md) | No |  |
| `cwes` | object[] | Yes |  |
| `cwe_ids` | string[] | Yes | A list of only the CWE IDs. |
| `credits` | object[] | Yes |  |
| `credits_detailed` | repository-advisory-credit[] | Yes |  |
| `collaborating_users` | simple-user[] | Yes | A list of users that collaborate on the advisory. |
| `collaborating_teams` | team[] | Yes | A list of teams that collaborate on the advisory. |
| `private_fork` | any | Yes | A temporary private fork of the advisory's repository for collaborating on a fix. |

## Nested Fields

### `identifiers`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `type` | enum: CVE, GHSA | Yes | The type of identifier. |
| `value` | string | Yes | The identifier value. |

### `submission`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `accepted` | boolean | Yes | Whether a private vulnerability report was accepted by the repository's administrators. |

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
| `login` | string | No | The username of the user credited. |
| `type` | [security-advisory-credit-types](security-advisory-credit-types.md) | No |  |

