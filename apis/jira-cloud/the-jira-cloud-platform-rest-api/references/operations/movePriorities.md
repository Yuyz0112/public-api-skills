# PUT /rest/api/3/priority/move

**Resource:** [Issue priorities](../resources/Issue-priorities.md)
**Move priorities**
**Operation ID:** `movePriorities`

Changes the order of issue priorities.

**[Permissions](#permissions) required:** *Administer Jira* [global permission](https://confluence.atlassian.com/x/x4dKLg).

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [ReorderIssuePriorities](../schemas/Reorder/ReorderIssuePriorities.md)

## Responses

| Status | Description |
|--------|-------------|
| 204 | Returned if the request is successful. |
| 400 | Returned if the request isn't valid. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 403 | Returned if the user doesn't have the necessary permission. |
| 404 | Returned if the issue priority isn't found. |

## Security

- **basicAuth**
- **OAuth2**: manage:jira-configuration
