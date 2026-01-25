# deployment-branch-policy

Details of a deployment branch or tag policy.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | integer | No | The unique identifier of the branch or tag policy. |
| `node_id` | string | No |  |
| `name` | string | No | The name pattern that branches or tags must match in order to deploy to the environment. |
| `type` | enum: branch, tag | No | Whether this rule targets a branch or tag. |

