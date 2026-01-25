# runner-groups-org

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | number | Yes |  |
| `name` | string | Yes |  |
| `visibility` | string | Yes |  |
| `default` | boolean | Yes |  |
| `selected_repositories_url` | string | No | Link to the selected repositories resource for this runner group. Not present unless visibility was set to `selected` |
| `runners_url` | string | Yes |  |
| `hosted_runners_url` | string | No |  |
| `network_configuration_id` | string | No | The identifier of a hosted compute network configuration. |
| `inherited` | boolean | Yes |  |
| `inherited_allows_public_repositories` | boolean | No |  |
| `allows_public_repositories` | boolean | Yes |  |
| `workflow_restrictions_read_only` | boolean | No | If `true`, the `restricted_to_workflows` and `selected_workflows` fields cannot be modified. |
| `restricted_to_workflows` | boolean | No | If `true`, the runner group will be restricted to running only the workflows specified in the `selected_workflows` array. |
| `selected_workflows` | string[] | No | List of workflows the runner group should be allowed to run. This setting will be ignored unless `restricted_to_workflows` is set to `true`. |

