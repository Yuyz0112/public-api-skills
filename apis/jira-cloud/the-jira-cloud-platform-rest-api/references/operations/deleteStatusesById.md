# DELETE /rest/api/3/statuses

**Resource:** [Status](../resources/Status.md)
**Bulk delete Statuses**
**Operation ID:** `deleteStatusesById`

Deletes statuses by ID.

**[Permissions](#permissions) required:**

 *  *Administer projects* [project permission.](https://confluence.atlassian.com/x/yodKLg)
 *  *Administer Jira* [project permission.](https://confluence.atlassian.com/x/yodKLg)

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | query | string[] | Yes | The list of status IDs. To include multiple IDs, provide an ampersand-separated list. For example, id=10000&id=10001.

Min items `1`, Max items `50` |

## Responses

| Status | Description |
|--------|-------------|
| 204 | Returned if the request is successful. |
| 400 | Returned if the request is not valid. |
| 401 | Returned if the authentication credentials are incorrect or missing, or the caller doesn't have permissions to perform the operation. |

## Security

- **basicAuth**
- **OAuth2**: manage:jira-configuration
