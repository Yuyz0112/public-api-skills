# dependabot-alert-security-advisory

Details for the GitHub Security Advisory.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `ghsa_id` | string | Yes | The unique GitHub Security Advisory ID assigned to the advisory. |
| `cve_id` | string | Yes | The unique CVE ID assigned to the advisory. |
| `summary` | string | Yes | A short, plain text summary of the advisory. |
| `description` | string | Yes | A long-form Markdown-supported description of the advisory. |
| `vulnerabilities` | dependabot-alert-security-vulnerability[] | Yes | Vulnerable version range information for the advisory. |
| `severity` | enum: low, medium, high... | Yes | The severity of the advisory. |
| `cvss` | object | Yes | Details for the advisory pertaining to the Common Vulnerability Scoring System. |
| `cvss_severities` | [cvss-severities](cvss-severities.md) | No |  |
| `epss` | [security-advisory-epss](security-advisory-epss.md) | No |  |
| `cwes` | object[] | Yes | Details for the advisory pertaining to Common Weakness Enumeration. |
| `identifiers` | object[] | Yes | Values that identify this advisory among security information sources. |
| `references` | object[] | Yes | Links to additional advisory information. |
| `published_at` | string (date-time) | Yes | The time that the advisory was published in ISO 8601 format: `YYYY-MM-DDTHH:MM:SSZ`. |
| `updated_at` | string (date-time) | Yes | The time that the advisory was last modified in ISO 8601 format: `YYYY-MM-DDTHH:MM:SSZ`. |
| `withdrawn_at` | string (date-time) | Yes | The time that the advisory was withdrawn in ISO 8601 format: `YYYY-MM-DDTHH:MM:SSZ`. |

## Nested Fields

### `cvss`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `score` | number | Yes | The overall CVSS score of the advisory. |
| `vector_string` | string | Yes | The full CVSS vector string for the advisory. |

### `cwes`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `cwe_id` | string | Yes | The unique CWE ID. |
| `name` | string | Yes | The short, plain text name of the CWE. |

### `identifiers`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `type` | enum: CVE, GHSA | Yes | The type of advisory identifier. |
| `value` | string | Yes | The value of the advisory identifer. |

### `references`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `url` | string (uri) | Yes | The URL of the reference. |

