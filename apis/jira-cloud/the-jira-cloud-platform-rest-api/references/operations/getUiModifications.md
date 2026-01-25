# GET /rest/api/3/uiModifications

**Resource:** [UI modifications (apps)](../resources/UI-modifications-apps.md)
**Get UI modifications**
**Operation ID:** `getUiModifications`

Gets UI modifications. UI modifications can only be retrieved by Forge apps.

**[Permissions](#permissions) required:** None.

The new `read:app-data:jira` OAuth scope is 100% optional now, and not using it won't break your app. However, we recommend adding it to your app's scope list because we will eventually make it mandatory.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `startAt` | query | integer (int64) | No | The index of the first item to return in a page of results (page offset). |
| `maxResults` | query | integer (int32) | No | The maximum number of items to return per page. |
| `expand` | query | string | No | Use expand to include additional information in the response. This parameter accepts a comma-separated list. Expand options include:

 *  `data` Returns UI modification data.
 *  `contexts` Returns UI modification contexts. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 400 | Returned if the request is not valid. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 403 | Returned if the request is not from a Forge app. |

**Success Response Schema:**

[PageBeanUiModificationDetails](../schemas/Page/PageBeanUiModificationDetails.md)

## Security

- **basicAuth**
- **OAuth2**: read:jira-work
