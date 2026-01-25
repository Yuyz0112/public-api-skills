# PermissionPayloadDTO

The payload to create a permission scheme

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `addAddonRole` | boolean | No | Configuration to generate addon role. Default is false if null. Only applies to GLOBAL-scoped permission scheme |
| `description` | string | No | The description of the permission scheme |
| `grants` | PermissionGrantDTO[] | No | List of permission grants |
| `name` | string | No | The name of the permission scheme |
| `onConflict` | enum: FAIL, USE, NEW | No | The strategy to use when there is a conflict with an existing permission scheme. FAIL - Fail execution, this always needs to be unique; USE - Use the existing entity and ignore new entity parameters; NEW - If the entity exist, try and create a new one with a different name |
| `pcri` | [ProjectCreateResourceIdentifier](ProjectCreateResourceIdentifier.md) | No |  |

