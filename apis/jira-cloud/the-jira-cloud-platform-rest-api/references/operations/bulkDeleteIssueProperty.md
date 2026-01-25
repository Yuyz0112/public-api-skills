# DELETE /rest/api/3/issue/properties/{propertyKey}

**Resource:** [Issue properties](../resources/Issue-properties.md)
**Bulk delete issue property**
**Operation ID:** `bulkDeleteIssueProperty`

Deletes a property value from multiple issues. The issues to be updated can be specified by filter criteria.

The criteria the filter used to identify eligible issues are:

 *  `entityIds` Only issues from this list are eligible.
 *  `currentValue` Only issues with the property set to this value are eligible.

If both criteria is specified, they are joined with the logical *AND*: only issues that satisfy both criteria are considered eligible.

If no filter criteria are specified, all the issues visible to the user and where the user has the EDIT\_ISSUES permission for the issue are considered eligible.

This operation is:

 *  transactional, either the property is deleted from all eligible issues or, when errors occur, no properties are deleted.
 *  [asynchronous](#async). Follow the `location` link in the response to determine the status of the task and use [Get task](#api-rest-api-3-task-taskId-get) to obtain subsequent updates.

**[Permissions](#permissions) required:**

 *  *Browse projects* [ project permission](https://confluence.atlassian.com/x/yodKLg) for each project containing issues.
 *  If [issue-level security](https://confluence.atlassian.com/x/J4lKLg) is configured, issue-level security permission to view the issue.
 *  *Edit issues* [project permission](https://confluence.atlassian.com/x/yodKLg) for each issue.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `propertyKey` | path | string | Yes | The key of the property. |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [IssueFilterForBulkPropertyDelete](../schemas/Issue/IssueFilterForBulkPropertyDelete.md)

## Responses

| Status | Description |
|--------|-------------|
| 303 | Returned if the request is successful. |
| 400 | Returned if the request is invalid. |
| 401 | Returned if the authentication credentials are incorrect or missing. |

## Security

- **basicAuth**
- **OAuth2**: write:jira-work
