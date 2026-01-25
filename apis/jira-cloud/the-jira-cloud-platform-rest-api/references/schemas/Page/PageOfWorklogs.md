# PageOfWorklogs

Paginated list of worklog details

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `maxResults` | integer (int32) | No | The maximum number of results that could be on the page. |
| `startAt` | integer (int32) | No | The index of the first item returned on the page. |
| `total` | integer (int32) | No | The number of results on the page. |
| `worklogs` | Worklog[] | No | List of worklogs. |

