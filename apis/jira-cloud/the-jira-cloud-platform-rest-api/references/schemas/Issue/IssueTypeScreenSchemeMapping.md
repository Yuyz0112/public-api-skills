# IssueTypeScreenSchemeMapping

The IDs of the screen schemes for the issue type IDs.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `issueTypeId` | string | Yes | The ID of the issue type or *default*. Only issue types used in classic projects are accepted. An entry for *default* must be provided and defines the mapping for all issue types without a screen scheme. |
| `screenSchemeId` | string | Yes | The ID of the screen scheme. Only screen schemes used in classic projects are accepted. |

