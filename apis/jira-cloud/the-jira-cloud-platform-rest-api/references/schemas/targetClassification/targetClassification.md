# targetClassification

Classification mapping for classifications in source issues to respective target classification.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `classifications` | object | Yes | An object with the key as the ID of the target classification and value with the list of the IDs of the current source classifications. |
| `issueType` | string | No | ID of the source issueType to which issues present in `issueIdOrKeys` belongs. |
| `projectKeyOrId` | string | No | ID or key of the source project to which issues present in `issueIdOrKeys` belongs. |

