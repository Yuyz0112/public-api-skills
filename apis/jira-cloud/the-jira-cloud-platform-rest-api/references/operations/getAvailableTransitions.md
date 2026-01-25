# GET /rest/api/3/bulk/issues/transition

**Resource:** [Issue bulk operations](../resources/Issue-bulk-operations.md)
**Get available transitions**
**Operation ID:** `getAvailableTransitions`

Use this API to retrieve a list of transitions available for the specified issues that can be used or bulk transition operations. You can submit either single or multiple issues in the query to obtain the available transitions.

The response will provide the available transitions for issues, organized by their respective workflows. **Only the transitions that are common among the issues within that workflow and do not involve any additional field updates will be included.** For bulk transitions that require additional field updates, please utilise the Jira Cloud UI.

You can request available transitions for up to 1,000 issues in a single operation. This API uses pagination to return responses, delivering 50 workflows at a time.

**[Permissions](#permissions) required:**

 *  Global bulk change [permission](https://support.atlassian.com/jira-cloud-administration/docs/manage-global-permissions/).
 *  Transition [issues permission](https://support.atlassian.com/jira-cloud-administration/docs/permissions-for-company-managed-projects/#Transition-issues/) in all projects that contain the selected issues.
 *  Browse [project permission](https://support.atlassian.com/jira-cloud-administration/docs/manage-project-permissions/) in all projects that contain the selected issues.
 *  If [issue-level security](https://confluence.atlassian.com/x/J4lKLg) is configured, issue-level security permission to view the issue.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `issueIdsOrKeys` | query | string | Yes | Comma (,) separated Ids or keys of the issues to get transitions available for them. |
| `endingBefore` | query | string | No | (Optional)The end cursor for use in pagination. |
| `startingAfter` | query | string | No | (Optional)The start cursor for use in pagination. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 400 | Returned if the request is not valid. For example, if a provided issue ID or key is invalid. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 403 | Returned if the user does not have the necessary permission. |

**Success Response Schema:**

[BulkTransitionGetAvailableTransitions](../schemas/Bulk/BulkTransitionGetAvailableTransitions.md)

## Security

- **basicAuth**
- **OAuth2**: read:jira-work
