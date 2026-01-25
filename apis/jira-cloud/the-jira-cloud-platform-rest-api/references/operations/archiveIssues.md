# PUT /rest/api/3/issue/archive

**Resource:** [Issues](../resources/Issues.md)
**Archive issue(s) by issue ID/key**
**Operation ID:** `archiveIssues`

Enables admins to archive up to 1000 issues in a single request using issue ID/key, returning details of the issue(s) archived in the process and the errors encountered, if any.

**Note that:**

 *  you can't archive subtasks directly, only through their parent issues
 *  you can only archive issues from software, service management, and business projects

**[Permissions](#permissions) required:** Jira admin or site admin: [global permission](https://confluence.atlassian.com/x/x4dKLg)

**License required:** Premium or Enterprise

**Signed-in users only:** This API can't be accessed anonymously.

  


## Request Body

Contains a list of issue keys or IDs to be archived.

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [IssueArchivalSyncRequest](../schemas/Issue/IssueArchivalSyncRequest.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if there is at least one valid issue to archive in the request. The return message will include the count of archived issues and subtasks, as well as error details for issues which failed to get archived. |
| 400 | Returned if none of the issues in the request can be archived. Possible reasons:

 *  the issues weren't found
 *  the issues are subtasks
 *  the issues belong to unlicensed projects
 *  the issues belong to archived projects |
| 401 | Returned if no issues were archived because the provided authentication credentials are either missing or invalid. |
| 403 | Returned if no issues were archived because the user lacks the required Jira admin or site admin permissions. |
| 412 | Returned if one or more issues were successfully archived, but the operation was incomplete because the number of issue IDs or keys provided exceeds 1000. |

**Success Response Schema:**

[IssueArchivalSyncResponse](../schemas/Issue/IssueArchivalSyncResponse.md)

## Security

- **basicAuth**
- **OAuth2**: write:jira-work
