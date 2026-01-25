# POST /rest/api/3/issue/properties/multi

**Resource:** [Issue properties](../resources/Issue-properties.md)
**Bulk set issue properties by issue**
**Operation ID:** `bulkSetIssuePropertiesByIssue`

Sets or updates entity property values on issues. Up to 10 entity properties can be specified for each issue and up to 100 issues included in the request.

The value of the request body must be a [valid](http://tools.ietf.org/html/rfc4627), non-empty JSON.

This operation is:

 *  [asynchronous](#async). Follow the `location` link in the response to determine the status of the task and use [Get task](#api-rest-api-3-task-taskId-get) to obtain subsequent updates.
 *  non-transactional. Updating some entities may fail. Such information will available in the task result.

**[Permissions](#permissions) required:**

 *  *Browse projects* and *Edit issues* [project permissions](https://confluence.atlassian.com/x/yodKLg) for the project containing the issue.
 *  If [issue-level security](https://confluence.atlassian.com/x/J4lKLg) is configured, issue-level security permission to view the issue.

## Request Body

Details of the issue properties to be set or updated. Note that if an issue is not found, it is ignored.

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [MultiIssueEntityProperties](../schemas/Multi/MultiIssueEntityProperties.md)

## Responses

| Status | Description |
|--------|-------------|
| 303 | Returned if the operation is successful. |
| 400 | Return if the request is invalid. |
| 401 | Returned if the authentication credentials are incorrect. |
| 403 | Return if the user does not have the necessary permission. |

## Security

- **basicAuth**
- **OAuth2**: write:jira-work
