# self-hosted-runners-settings

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `enabled_repositories` | enum: all, selected, none | Yes | The policy that controls whether self-hosted runners can be used by repositories in the organization |
| `selected_repositories_url` | string | No | The URL to the endpoint for managing selected repositories for self-hosted runners in the organization |

