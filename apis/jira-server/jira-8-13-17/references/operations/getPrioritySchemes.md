# GET /priorityschemes

**Resource:** [priorityschemes](../resources/priorityschemes.md)
**Operation ID:** `getPrioritySchemes`

Returns all priority schemes.

 All project keys associated with the priority scheme will only be returned if additional query parameter is provided <code>expand=schemes.projectKeys</code>.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `startAt` | query | integer (int64) | No | the page offset, if not specified then defaults to 0 |
| `maxResults` | query | integer (int32) | No | how many results on the page should be included. Defaults to 100, maximum is 1000. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful Response |

