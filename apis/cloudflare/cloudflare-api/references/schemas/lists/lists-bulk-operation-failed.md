# lists_bulk_operation_failed

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `completed` | [lists_completed](lists-completed.md) | Yes |  |
| `error` | string | Yes | A message describing the error when the status is `failed`. |
| `id` | [lists_operation_id](lists-operation-id.md) | Yes |  |
| `status` | enum: failed | Yes | The current status of the asynchronous operation. |

