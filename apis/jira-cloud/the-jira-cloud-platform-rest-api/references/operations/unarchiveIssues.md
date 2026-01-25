# PUT /rest/api/3/issue/unarchive

**Resource:** [Issues](../resources/Issues.md)
**Unarchive issue(s) by issue keys/ID**
**Operation ID:** `unarchiveIssues`

Enables admins to unarchive up to 1000 issues in a single request using issue ID/key, returning details of the issue(s) unarchived in the process and the errors encountered, if any.

**Note that:**

 *  you can't unarchive subtasks directly, only through their parent issues
 *  you can only unarchive issues from software, service management, and business projects

**[Permissions](#permissions) required:** Jira admin or site admin: [global permission](https://confluence.atlassian.com/x/x4dKLg)

**License required:** Premium or Enterprise

**Signed-in users only:** This API can't be accessed anonymously.

  


## Request Body

Contains a list of issue keys or IDs to be unarchived.

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [IssueArchivalSyncRequest](../schemas/Issue/IssueArchivalSyncRequest.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if there is at least one valid issue to unarchive in the request. It will return the count of unarchived issues, which also includes the count of the subtasks unarchived, and it will show the detailed errors for those issues which are not unarchived. |
| 400 | Returned if none of the issues in the request are eligible to be unarchived. Possible reasons:

 *  the issues weren't found
 *  the issues are subtasks
 *  the issues belong to archived projects |
| 401 | Returned if no issues were unarchived because the provided authentication credentials are either missing or invalid. |
| 403 | Returned if no issues were unarchived because the user lacks the required Jira admin or site admin permissions. |
| 412 | Returned if one or more issues were successfully unarchived, but the operation was incomplete because the number of issue IDs or keys provided exceeds 1000. |

**Success Response Schema:**

[IssueArchivalSyncResponse](../schemas/Issue/IssueArchivalSyncResponse.md)

## Security

- **basicAuth**
- **OAuth2**: write:jira-work
