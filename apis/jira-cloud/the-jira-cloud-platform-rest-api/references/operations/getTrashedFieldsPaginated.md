# GET /rest/api/3/field/search/trashed

**Resource:** [Issue fields](../resources/Issue-fields.md)
**Get fields in trash paginated**
**Operation ID:** `getTrashedFieldsPaginated`

Returns a [paginated](#pagination) list of fields in the trash. The list may be restricted to fields whose field name or description partially match a string.

Only custom fields can be queried, `type` must be set to `custom`.

**[Permissions](#permissions) required:** *Administer Jira* [global permission](https://confluence.atlassian.com/x/x4dKLg).

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `startAt` | query | integer (int64) | No | The index of the first item to return in a page of results (page offset). |
| `maxResults` | query | integer (int32) | No | The maximum number of items to return per page. |
| `id` | query | string[] | No |  |
| `query` | query | string | No | String used to perform a case-insensitive partial match with field names or descriptions. |
| `expand` | query | enum: name, -name, +name... | No |  |
| `orderBy` | query | string | No | [Order](#ordering) the results by a field:

 *  `name` sorts by the field name
 *  `trashDate` sorts by the date the field was moved to the trash
 *  `plannedDeletionDate` sorts by the planned deletion date |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 400 | Returned if the request is invalid. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 403 | Returned if the user does not have the necessary permission. |

**Success Response Schema:**

[PageBeanField](../schemas/Page/PageBeanField.md)

## Security

- **basicAuth**
- **OAuth2**: read:jira-work
