# GET /rest/api/3/field/{fieldId}/screens

**Resource:** [Screens](../resources/Screens.md)
**Get screens for a field**
**Operation ID:** `getScreensForField`

Returns a [paginated](#pagination) list of the screens a field is used in.

**[Permissions](#permissions) required:** *Administer Jira* [global permission](https://confluence.atlassian.com/x/x4dKLg).

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `fieldId` | path | string | Yes | The ID of the field to return screens for. |
| `startAt` | query | integer (int64) | No | The index of the first item to return in a page of results (page offset). |
| `maxResults` | query | integer (int32) | No | The maximum number of items to return per page. |
| `expand` | query | string | No | Use [expand](#expansion) to include additional information about screens in the response. This parameter accepts `tab` which returns details about the screen tabs the field is used in. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 403 | Returned if the user does not have the necessary permission. |

**Success Response Schema:**

[PageBeanScreenWithTab](../schemas/Page/PageBeanScreenWithTab.md)

## Security

- **basicAuth**
- **OAuth2**: manage:jira-project
