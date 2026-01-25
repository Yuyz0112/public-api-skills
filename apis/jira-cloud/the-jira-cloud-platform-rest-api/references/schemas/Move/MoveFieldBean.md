# MoveFieldBean

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `after` | string (uri) | No | The ID of the screen tab field after which to place the moved screen tab field. Required if `position` isn't provided. |
| `position` | enum: Earlier, Later, First... | No | The named position to which the screen tab field should be moved. Required if `after` isn't provided. |

