# secret-scanning-pattern-configuration

A collection of secret scanning patterns and their settings related to push protection.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `pattern_config_version` | [secret-scanning-row-version](secret-scanning-row-version.md) | No |  |
| `provider_pattern_overrides` | secret-scanning-pattern-override[] | No | Overrides for partner patterns. |
| `custom_pattern_overrides` | secret-scanning-pattern-override[] | No | Overrides for custom patterns defined by the organization. |

