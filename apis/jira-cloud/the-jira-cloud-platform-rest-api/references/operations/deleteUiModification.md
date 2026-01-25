# DELETE /rest/api/3/uiModifications/{uiModificationId}

**Resource:** [UI modifications (apps)](../resources/UI-modifications-apps.md)
**Delete UI modification**
**Operation ID:** `deleteUiModification`

Deletes a UI modification. All the contexts that belong to the UI modification are deleted too. UI modification can only be deleted by Forge apps.

**[Permissions](#permissions) required:** None.

The new `write:app-data:jira` OAuth scope is 100% optional now, and not using it won't break your app. However, we recommend adding it to your app's scope list because we will eventually make it mandatory.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `uiModificationId` | path | string | Yes | The ID of the UI modification. |

## Responses

| Status | Description |
|--------|-------------|
| 204 | Returned if the UI modification is deleted. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 403 | Returned if the request is not from a Forge app. |
| 404 | Returned if the UI modification is not found. |

## Security

- **basicAuth**
- **OAuth2**
