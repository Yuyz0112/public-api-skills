# ContentItem

Represents the content to redact

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `entityId` | string | Yes | The ID of the content entity.

 *  For redacting an issue field, this will be the field ID (e.g., summary, customfield\_10000).
 *  For redacting a comment, this will be the comment ID.
 *  For redacting a worklog, this will be the worklog ID. |
| `entityType` | enum: issuefieldvalue, issue-comment, issue-worklog | Yes | The type of the entity to redact; It will be one of the following:

 *  **issuefieldvalue** \- To redact in issue fields
 *  **issue-comment** \- To redact in issue comments.
 *  **issue-worklog** \- To redact in issue worklogs |
| `id` | string | Yes | This would be the issue ID |

