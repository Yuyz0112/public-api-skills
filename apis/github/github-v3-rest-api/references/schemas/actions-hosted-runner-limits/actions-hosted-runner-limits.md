# actions-hosted-runner-limits

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `public_ips` | object | Yes | Provides details of static public IP limits for GitHub-hosted Hosted Runners |

## Nested Fields

### `public_ips`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `maximum` | integer | Yes | The maximum number of static public IP addresses that can be used for Hosted Runners. |
| `current_usage` | integer | Yes | The current number of static public IP addresses in use by Hosted Runners. |

