# GET /rest/api/3/statuses/{statusId}/projectUsages

**Resource:** [Status](../resources/Status.md)
**Get project usages by status**
**Operation ID:** `getProjectUsagesForStatus`

Returns a page of projects using a given status.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `statusId` | path | string | Yes | The statusId to fetch project usages for |
| `nextPageToken` | query | string | No | The cursor for pagination |
| `maxResults` | query | integer (int32) | No | The maximum number of results to return. Must be an integer between 1 and 200. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 400 | Returned if the request is not valid. |
| 401 | Returned if the authentication credentials are incorrect or missing, or the caller doesn't have permissions to perform the operation. |
| 404 | Returned if the status with the given ID does not exist. |

**Success Response Schema:**

[StatusProjectUsageDTO](../schemas/Status/StatusProjectUsageDTO.md)

## Security

- **basicAuth**
- **OAuth2**: manage:jira-configuration
