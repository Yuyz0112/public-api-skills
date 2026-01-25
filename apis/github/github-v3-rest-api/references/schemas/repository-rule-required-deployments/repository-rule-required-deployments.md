# repository-rule-required-deployments

Choose which environments must be successfully deployed to before refs can be pushed into a ref that matches this rule.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `type` | enum: required_deployments | Yes |  |
| `parameters` | object | No |  |

## Nested Fields

### `parameters`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `required_deployment_environments` | string[] | Yes | The environments that must be successfully deployed to before branches can be merged. |

