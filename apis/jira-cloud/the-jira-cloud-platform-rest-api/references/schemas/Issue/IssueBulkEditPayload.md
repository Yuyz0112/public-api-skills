# IssueBulkEditPayload

Issue Bulk Edit Payload

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `editedFieldsInput` | any | Yes | An object that defines the values to be updated in specified fields of an issue. The structure and content of this parameter vary depending on the type of field being edited. Although the order is not significant, ensure that field IDs align with those in selectedActions. |
| `selectedActions` | string[] | Yes | List of all the field IDs that are to be bulk edited. Each field ID in this list corresponds to a specific attribute of an issue that is set to be modified in the bulk edit operation. The relevant field ID can be obtained by calling the Bulk Edit Get Fields REST API (documentation available on this page itself). |
| `selectedIssueIdsOrKeys` | string[] | Yes | List of issue IDs or keys which are to be bulk edited. These IDs or keys can be from different projects and issue types. |
| `sendBulkNotification` | boolean | No | A boolean value that indicates whether to send a bulk change notification when the issues are being edited.

If `true`, dispatches a bulk notification email to users about the updates. |

