# repository-rule-params-code-scanning-tool

A tool that must provide code scanning results for this rule to pass.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `alerts_threshold` | enum: none, errors, errors_and_warnings... | Yes | The severity level at which code scanning results that raise alerts block a reference update. For more information on alert severity levels, see "[About code scanning alerts](https://docs.github.com/code-security/code-scanning/managing-code-scanning-alerts/about-code-scanning-alerts#about-alert-severity-and-security-severity-levels)." |
| `security_alerts_threshold` | enum: none, critical, high_or_higher... | Yes | The severity level at which code scanning results that raise security alerts block a reference update. For more information on security severity levels, see "[About code scanning alerts](https://docs.github.com/code-security/code-scanning/managing-code-scanning-alerts/about-code-scanning-alerts#about-alert-severity-and-security-severity-levels)." |
| `tool` | string | Yes | The name of a code scanning tool |

