# DELETE /rest/api/3/screens/{screenId}

**Resource:** [Screens](../resources/Screens.md)
**Delete screen**
**Operation ID:** `deleteScreen`

Deletes a screen. A screen cannot be deleted if it is used in a screen scheme, workflow, or workflow draft.

Only screens used in classic projects can be deleted.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `screenId` | path | integer (int64) | Yes | The ID of the screen. |

## Responses

| Status | Description |
|--------|-------------|
| 204 | Returned if the request is successful. |
| 400 | Returned if the request is not valid. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 403 | Returned if the user does not have the necessary permission. |
| 404 | Returned if the screen is not found. |

## Security

- **basicAuth**
- **OAuth2**: manage:jira-project
