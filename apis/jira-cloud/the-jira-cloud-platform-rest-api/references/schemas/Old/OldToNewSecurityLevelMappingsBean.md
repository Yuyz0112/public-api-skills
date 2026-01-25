# OldToNewSecurityLevelMappingsBean

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `newLevelId` | string | Yes | The new issue security level ID. Providing null will clear the assigned old level from issues. |
| `oldLevelId` | string | Yes | The old issue security level ID. Providing null will remap all issues without any assigned levels. |

