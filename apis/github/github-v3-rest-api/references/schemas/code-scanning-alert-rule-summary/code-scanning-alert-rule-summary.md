# code-scanning-alert-rule-summary

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | string | No | A unique identifier for the rule used to detect the alert. |
| `name` | string | No | The name of the rule used to detect the alert. |
| `severity` | enum: none, note, warning... | No | The severity of the alert. |
| `security_severity_level` | enum: low, medium, high... | No | The security severity of the alert. |
| `description` | string | No | A short description of the rule used to detect the alert. |
| `full_description` | string | No | A description of the rule used to detect the alert. |
| `tags` | string[] | No | A set of tags applicable for the rule. |
| `help` | string | No | Detailed documentation for the rule as GitHub Flavored Markdown. |
| `help_uri` | string | No | A link to the documentation for the rule used to detect the alert. |

