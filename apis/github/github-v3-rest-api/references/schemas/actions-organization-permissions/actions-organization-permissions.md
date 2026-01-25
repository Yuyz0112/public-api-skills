# actions-organization-permissions

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `enabled_repositories` | [enabled-repositories](enabled-repositories.md) | Yes |  |
| `selected_repositories_url` | string | No | The API URL to use to get or set the selected repositories that are allowed to run GitHub Actions, when `enabled_repositories` is set to `selected`. |
| `allowed_actions` | [allowed-actions](allowed-actions.md) | No |  |
| `selected_actions_url` | [selected-actions-url](selected-actions-url.md) | No |  |
| `sha_pinning_required` | [sha-pinning-required](sha-pinning-required.md) | No |  |

