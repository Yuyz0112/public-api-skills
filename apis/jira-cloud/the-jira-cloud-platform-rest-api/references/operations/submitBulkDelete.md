# POST /rest/api/3/bulk/issues/delete

**Resource:** [Issue bulk operations](../resources/Issue-bulk-operations.md)
**Bulk delete issues**
**Operation ID:** `submitBulkDelete`

Use this API to submit a bulk delete request. You can delete up to 1,000 issues in a single operation.

**[Permissions](#permissions) required:**

 *  Global bulk change [permission](https://support.atlassian.com/jira-cloud-administration/docs/manage-global-permissions/).
 *  Delete [issues permission](https://support.atlassian.com/jira-cloud-administration/docs/permissions-for-company-managed-projects/#Delete-issues/) in all projects that contain the selected issues.
 *  Browse [project permission](https://support.atlassian.com/jira-cloud-administration/docs/manage-project-permissions/) in all projects that contain the selected issues.
 *  If [issue-level security](https://confluence.atlassian.com/x/J4lKLg) is configured, issue-level security permission to view the issue.

## Request Body

The request body containing the issues to be deleted.

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [IssueBulkDeletePayload](../schemas/Issue/IssueBulkDeletePayload.md)

## Responses

| Status | Description |
|--------|-------------|
| 201 | Returned if the request is successful. |
| 400 | Returned if the request is invalid. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 403 | Returned if the user does not have the necessary permission. |

**Success Response Schema:**

[SubmittedBulkOperation](../schemas/Submitted/SubmittedBulkOperation.md)

## Security

- **basicAuth**
- **OAuth2**: write:jira-work
