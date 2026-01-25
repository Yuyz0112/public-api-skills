# IssueBulkDeletePayload

Issue Bulk Delete Payload

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `selectedIssueIdsOrKeys` | string[] | Yes | List of issue IDs or keys which are to be bulk deleted. These IDs or keys can be from different projects and issue types. |
| `sendBulkNotification` | boolean | No | A boolean value that indicates whether to send a bulk change notification when the issues are being deleted.

If `true`, dispatches a bulk notification email to users about the updates. |

