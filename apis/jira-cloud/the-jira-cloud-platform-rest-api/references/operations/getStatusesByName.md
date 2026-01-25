# GET /rest/api/3/statuses/byNames

**Resource:** [Status](../resources/Status.md)
**Bulk get statuses by name**
**Operation ID:** `getStatusesByName`

Returns a list of the statuses specified by one or more status names.

**[Permissions](#permissions) required:**

 *  *Administer projects* [project permission.](https://confluence.atlassian.com/x/yodKLg)
 *  *Administer Jira* [project permission.](https://confluence.atlassian.com/x/yodKLg)
 *  *Browse projects* [project permission.](https://confluence.atlassian.com/x/yodKLg)

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `name` | query | string[] | Yes | The list of status names. To include multiple names, provide an ampersand-separated list. For example, name=nameXX&name=nameYY.

Min items `1`, Max items `50` |
| `projectId` | query | string | No | The project the status is part of or null for global statuses. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 400 | Returned if the request is not valid. |
| 401 | Returned if the authentication credentials are incorrect or missing, or the caller doesn't have permissions to perform the operation. |

**Success Response Schema:**

Array of [JiraStatus](../schemas/Jira/JiraStatus.md)

## Security

- **basicAuth**
- **OAuth2**: manage:jira-configuration
