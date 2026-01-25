# firewall_schemas-configuration

The configuration object for the current rule.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `target` | string | No | The configuration target for this rule. You must set the target to `ua` for User Agent Blocking rules. |
| `value` | string | No | The exact user agent string to match. This value will be compared to the received `User-Agent` HTTP header value. |

