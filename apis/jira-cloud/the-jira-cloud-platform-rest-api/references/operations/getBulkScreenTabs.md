# GET /rest/api/3/screens/tabs

**Resource:** [Screen tabs](../resources/Screen-tabs.md)
**Get bulk screen tabs**
**Operation ID:** `getBulkScreenTabs`

Returns the list of tabs for a bulk of screens.

**[Permissions](#permissions) required:**

 *  *Administer Jira* [global permission](https://confluence.atlassian.com/x/x4dKLg).

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `screenId` | query | integer[] | No | The list of screen IDs. To include multiple screen IDs, provide an ampersand-separated list. For example, `screenId=10000&screenId=10001`. |
| `tabId` | query | integer[] | No | The list of tab IDs. To include multiple tab IDs, provide an ampersand-separated list. For example, `tabId=10000&tabId=10001`. |
| `startAt` | query | integer (int64) | No | The index of the first item to return in a page of results (page offset). |
| `maxResult` | query | integer (int32) | No | The maximum number of items to return per page. The maximum number is 100, |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 400 | Returned if the screen ID or the tab ID is empty. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 403 | Returned if the user does not have the necessary permission. |

## Security

- **basicAuth**
- **OAuth2**: manage:jira-project
