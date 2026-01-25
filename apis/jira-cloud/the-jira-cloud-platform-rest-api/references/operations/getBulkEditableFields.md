# GET /rest/api/3/bulk/issues/fields

**Resource:** [Issue bulk operations](../resources/Issue-bulk-operations.md)
**Get bulk editable fields**
**Operation ID:** `getBulkEditableFields`

Use this API to get a list of fields visible to the user to perform bulk edit operations. You can pass single or multiple issues in the query to get eligible editable fields. This API uses pagination to return responses, delivering 50 fields at a time.

**[Permissions](#permissions) required:**

 *  Global bulk change [permission](https://support.atlassian.com/jira-cloud-administration/docs/manage-global-permissions/).
 *  Browse [project permission](https://support.atlassian.com/jira-cloud-administration/docs/manage-project-permissions/) in all projects that contain the selected issues.
 *  If [issue-level security](https://confluence.atlassian.com/x/J4lKLg) is configured, issue-level security permission to view the issue.
 *  Depending on the field, any field-specific permissions required to edit it.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `issueIdsOrKeys` | query | string | Yes | The IDs or keys of the issues to get editable fields from. |
| `searchText` | query | string | No | (Optional)The text to search for in the editable fields. |
| `endingBefore` | query | string | No | (Optional)The end cursor for use in pagination. |
| `startingAfter` | query | string | No | (Optional)The start cursor for use in pagination. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 400 | Returned if the request is not valid. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 403 | Returned if the user does not have the necessary permission. |
| 404 | Returned if no editable fields are found for the provided issue IDs. |

**Success Response Schema:**

[BulkEditGetFields](../schemas/Bulk/BulkEditGetFields.md)

## Security

- **basicAuth**
- **OAuth2**: read:jira-work
