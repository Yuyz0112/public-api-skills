# VersionMoveBean

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `after` | string (uri) | No | The URL (self link) of the version after which to place the moved version. Cannot be used with `position`. |
| `position` | enum: Earlier, Later, First... | No | An absolute position in which to place the moved version. Cannot be used with `after`. |

