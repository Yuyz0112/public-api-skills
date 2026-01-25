# GET /rest/api/3/worklog/deleted

**Resource:** [Issue worklogs](../resources/Issue-worklogs.md)
**Get IDs of deleted worklogs**
**Operation ID:** `getIdsOfWorklogsDeletedSince`

Returns a list of IDs and delete timestamps for worklogs deleted after a date and time.

This resource is paginated, with a limit of 1000 worklogs per page. Each page lists worklogs from oldest to youngest. If the number of items in the date range exceeds 1000, `until` indicates the timestamp of the youngest item on the page. Also, `nextPage` provides the URL for the next page of worklogs. The `lastPage` parameter is set to true on the last page of worklogs.

This resource does not return worklogs deleted during the minute preceding the request.

**[Permissions](#permissions) required:** Permission to access Jira.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `since` | query | integer (int64) | No | The date and time, as a UNIX timestamp in milliseconds, after which deleted worklogs are returned. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 401 | Returned if the authentication credentials are incorrect or missing. |

**Success Response Schema:**

[ChangedWorklogs](../schemas/Changed/ChangedWorklogs.md)

## Security

- **basicAuth**
- **OAuth2**: read:jira-work
