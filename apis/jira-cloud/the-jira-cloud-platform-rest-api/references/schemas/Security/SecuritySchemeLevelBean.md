# SecuritySchemeLevelBean

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `description` | string | No | The description of the issue security scheme level. |
| `isDefault` | boolean | No | Specifies whether the level is the default level. False by default. |
| `members` | SecuritySchemeLevelMemberBean[] | No | The list of level members which should be added to the issue security scheme level. |
| `name` | string | Yes | The name of the issue security scheme level. Must be unique. |

