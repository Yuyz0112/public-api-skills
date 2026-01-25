# DeleteAndReplaceVersionBean

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `customFieldReplacementList` | CustomFieldReplacement[] | No | An array of custom field IDs (`customFieldId`) and version IDs (`moveTo`) to update when the fields contain the deleted version. |
| `moveAffectedIssuesTo` | integer (int64) | No | The ID of the version to update `affectedVersion` to when the field contains the deleted version. |
| `moveFixIssuesTo` | integer (int64) | No | The ID of the version to update `fixVersion` to when the field contains the deleted version. |

