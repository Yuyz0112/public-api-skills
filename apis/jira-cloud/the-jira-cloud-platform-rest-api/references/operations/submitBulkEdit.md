# POST /rest/api/3/bulk/issues/fields

**Resource:** [Issue bulk operations](../resources/Issue-bulk-operations.md)
**Bulk edit issues**
**Operation ID:** `submitBulkEdit`

Use this API to submit a bulk edit request and simultaneously edit multiple issues. There are limits applied to the number of issues and fields that can be edited. A single request can accommodate a maximum of 1000 issues (including subtasks) and 200 fields.

**[Permissions](#permissions) required:**

 *  Global bulk change [permission](https://support.atlassian.com/jira-cloud-administration/docs/manage-global-permissions/).
 *  Browse [project permission](https://support.atlassian.com/jira-cloud-administration/docs/manage-project-permissions/) in all projects that contain the selected issues.
 *  Edit [issues permission](https://support.atlassian.com/jira-cloud-administration/docs/manage-project-permissions/) in all projects that contain the selected issues.
 *  If [issue-level security](https://confluence.atlassian.com/x/J4lKLg) is configured, issue-level security permission to view the issue.

## Request Body

The request body containing the issues to be edited and the new field values.

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [IssueBulkEditPayload](../schemas/Issue/IssueBulkEditPayload.md)

## Responses

| Status | Description |
|--------|-------------|
| 201 | Returned if the request is successful. |
| 400 | Returned if the request is invalid. |
| 401 | Returned if the authentication credentials are incorrect or missing. |

**Success Response Schema:**

[SubmittedBulkOperation](../schemas/Submitted/SubmittedBulkOperation.md)

## Security

- **basicAuth**
- **OAuth2**: write:jira-work
