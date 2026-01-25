# IssueTypeSchemeDetails

Details of an issue type scheme and its associated issue types.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `defaultIssueTypeId` | string | No | The ID of the default issue type of the issue type scheme. This ID must be included in `issueTypeIds`. |
| `description` | string | No | The description of the issue type scheme. The maximum length is 4000 characters. |
| `issueTypeIds` | string[] | Yes | The list of issue types IDs of the issue type scheme. At least one standard issue type ID is required. |
| `name` | string | Yes | The name of the issue type scheme. The name must be unique. The maximum length is 255 characters. |

