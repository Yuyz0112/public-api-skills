# immutable-releases-organization-settings

Check immutable releases settings for an organization.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `enforced_repositories` | enum: all, none, selected | Yes | The policy that controls how immutable releases are enforced in the organization. |
| `selected_repositories_url` | string | No | The API URL to use to get or set the selected repositories for immutable releases enforcement, when `enforced_repositories` is set to `selected`. |

