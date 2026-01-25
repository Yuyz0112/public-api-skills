# GET /rest/api/3/field/search

**Resource:** [Issue fields](../resources/Issue-fields.md)
**Get fields paginated**
**Operation ID:** `getFieldsPaginated`

Returns a [paginated](#pagination) list of fields for Classic Jira projects. The list can include:

 *  all fields
 *  specific fields, by defining `id`
 *  fields that contain a string in the field name or description, by defining `query`
 *  specific fields that contain a string in the field name or description, by defining `id` and `query`

Use `type` must be set to `custom` to show custom fields only.

**[Permissions](#permissions) required:** Permission to access Jira.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `startAt` | query | integer (int64) | No | The index of the first item to return in a page of results (page offset). |
| `maxResults` | query | integer (int32) | No | The maximum number of items to return per page. |
| `type` | query | string[] | No | The type of fields to search. |
| `id` | query | string[] | No | The IDs of the custom fields to return or, where `query` is specified, filter. |
| `query` | query | string | No | String used to perform a case-insensitive partial match with field names or descriptions. |
| `orderBy` | query | enum: contextsCount, -contextsCount, +contextsCount... | No | [Order](#ordering) the results by:

 *  `contextsCount` sorts by the number of contexts related to a field
 *  `lastUsed` sorts by the date when the value of the field last changed
 *  `name` sorts by the field name
 *  `screensCount` sorts by the number of screens related to a field |
| `expand` | query | string | No | Use [expand](#expansion) to include additional information in the response. This parameter accepts a comma-separated list. Expand options include:

 *  `key` returns the key for each field
 *  `stableId` returns the stableId for each field
 *  `lastUsed` returns the date when the value of the field last changed
 *  `screensCount` returns the number of screens related to a field
 *  `contextsCount` returns the number of contexts related to a field
 *  `isLocked` returns information about whether the field is locked
 *  `searcherKey` returns the searcher key for each custom field |
| `projectIds` | query | integer[] | No | The IDs of the projects to filter the fields by. Fields belonging to project Ids that the user does not have access to will not be returned |

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
