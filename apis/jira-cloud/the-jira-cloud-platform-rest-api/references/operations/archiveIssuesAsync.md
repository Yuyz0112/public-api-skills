# POST /rest/api/3/issue/archive

**Resource:** [Issues](../resources/Issues.md)
**Archive issue(s) by JQL**
**Operation ID:** `archiveIssuesAsync`

Enables admins to archive up to 100,000 issues in a single request using JQL, returning the URL to check the status of the submitted request.

You can use the [get task](https://developer.atlassian.com/cloud/jira/platform/rest/v3/api-group-tasks/#api-rest-api-3-task-taskid-get) and [cancel task](https://developer.atlassian.com/cloud/jira/platform/rest/v3/api-group-tasks/#api-rest-api-3-task-taskid-cancel-post) APIs to manage the request.

**Note that:**

 *  you can't archive subtasks directly, only through their parent issues
 *  you can only archive issues from software, service management, and business projects

**[Permissions](#permissions) required:** Jira admin or site admin: [global permission](https://confluence.atlassian.com/x/x4dKLg)

**License required:** Premium or Enterprise

**Signed-in users only:** This API can't be accessed anonymously.

**Rate limiting:** Only a single request per jira instance can be active at any given time.

  


## Request Body

A JQL query specifying the issues to archive. Note that subtasks can only be archived through their parent issues.

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [ArchiveIssueAsyncRequest](../schemas/Archive/ArchiveIssueAsyncRequest.md)

## Responses

| Status | Description |
|--------|-------------|
| 202 | Returns the URL to check the status of the submitted request. |
| 400 | Returned if no issues were archived due to a bad request, for example an invalid JQL query. |
| 401 | Returned if no issues were archived because the provided authentication credentials are either missing or invalid. |
| 403 | Returned if no issues were archived because the user lacks the required Jira admin or site admin permissions. |
| 412 | Returned if a request to archive issue(s) is already running. |

## Security

- **basicAuth**
- **OAuth2**: write:jira-work
