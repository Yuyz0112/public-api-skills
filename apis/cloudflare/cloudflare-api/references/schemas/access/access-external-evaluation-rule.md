# access_external_evaluation_rule

Create Allow or Block policies which evaluate the user based on custom criteria.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `external_evaluation` | object | Yes |  |

## Nested Fields

### `external_evaluation`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `evaluate_url` | string | Yes | The API endpoint containing your business logic. |
| `keys_url` | string | Yes | The API endpoint containing the key that Access uses to verify that the response came from your API. |

