# GET /rest/api/3/projects/fields

**Resource:** [Issue fields](../resources/Issue-fields.md)
**Get fields for projects**
**Operation ID:** `getProjectFields`

Returns a [paginated](#pagination) list of fields for the requested projects and work types.

Only fields that are available for the specified combination of projects and work types are returned. This endpoint allows filtering to specific fields if field IDs are provided.

**[Permissions](#permissions) required:** Permission to access Jira.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `startAt` | query | integer (int64) | No | The index of the first item to return in a page of results (page offset). |
| `maxResults` | query | integer (int32) | No | The maximum number of items to return per page. |
| `projectId` | query | integer[] | Yes | The IDs of projects to return fields for. |
| `workTypeId` | query | integer[] | Yes | The IDs of work types (issue types) to return fields for. |
| `fieldId` | query | string[] | No | The IDs of fields to return. If not provided, all fields are returned. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 400 | Returned if the request parameters are invalid. |
| 401 | Returned if authentication is missing. |
| 403 | Returned if the user does not have permission to view the projects or work types. |
| 404 | Returned if the endpoint is not enabled via feature flag. |

**Success Response Schema:**

[PageBean2ProjectFieldBean](../schemas/Page/PageBean2ProjectFieldBean.md)

## Security

- **basicAuth**
- **OAuth2**: read:jira-work
