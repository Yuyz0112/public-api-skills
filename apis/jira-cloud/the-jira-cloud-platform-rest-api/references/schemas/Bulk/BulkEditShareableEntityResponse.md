# BulkEditShareableEntityResponse

Details of a request to bulk edit shareable entity.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `action` | enum: changeOwner, changePermission, addPermission... | Yes | Allowed action for bulk edit shareable entity |
| `entityErrors` | object | No | The mapping dashboard id to errors if any. |

