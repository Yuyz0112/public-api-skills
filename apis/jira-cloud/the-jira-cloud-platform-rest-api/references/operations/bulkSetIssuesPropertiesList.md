# POST /rest/api/3/issue/properties

**Resource:** [Issue properties](../resources/Issue-properties.md)
**Bulk set issues properties by list**
**Operation ID:** `bulkSetIssuesPropertiesList`

Sets or updates a list of entity property values on issues. A list of up to 10 entity properties can be specified along with up to 10,000 issues on which to set or update that list of entity properties.

The value of the request body must be a [valid](http://tools.ietf.org/html/rfc4627), non-empty JSON. The maximum length of single issue property value is 32768 characters. This operation can be accessed anonymously.

This operation is:

 *  transactional, either all properties are updated in all eligible issues or, when errors occur, no properties are updated.
 *  [asynchronous](#async). Follow the `location` link in the response to determine the status of the task and use [Get task](#api-rest-api-3-task-taskId-get) to obtain subsequent updates.

**[Permissions](#permissions) required:**

 *  *Browse projects* and *Edit issues* [project permissions](https://confluence.atlassian.com/x/yodKLg) for the project containing the issue.
 *  If [issue-level security](https://confluence.atlassian.com/x/J4lKLg) is configured, issue-level security permission to view the issue.

## Request Body

Issue properties to be set or updated with values.

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [IssueEntityProperties](../schemas/Issue/IssueEntityProperties.md)

## Responses

| Status | Description |
|--------|-------------|
| 303 | Returned if the operation is successful. |
| 400 | Return if the request is invalid or the user does not have the necessary permission. |
| 401 | Returned if the authentication credentials are incorrect. |

## Security

- **basicAuth**
- **OAuth2**: write:jira-work
