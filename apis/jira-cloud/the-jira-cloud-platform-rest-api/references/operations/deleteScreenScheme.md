# DELETE /rest/api/3/screenscheme/{screenSchemeId}

**Resource:** [Screen schemes](../resources/Screen-schemes.md)
**Delete screen scheme**
**Operation ID:** `deleteScreenScheme`

Deletes a screen scheme. A screen scheme cannot be deleted if it is used in an issue type screen scheme.

Only screens schemes used in classic projects can be deleted.

**[Permissions](#permissions) required:** *Administer Jira* [global permission](https://confluence.atlassian.com/x/x4dKLg).

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `screenSchemeId` | path | string | Yes | The ID of the screen scheme. |

## Responses

| Status | Description |
|--------|-------------|
| 204 | Returned if the screen scheme is deleted. |
| 400 | Returned if the screen scheme is used in an issue type screen scheme. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 403 | Returned if the user does not have the necessary permission. |
| 404 | Returned if the screen scheme is not found. |

## Security

- **basicAuth**
- **OAuth2**: manage:jira-project
