# GET /project/{projectIdOrKey}/version

**Resource:** [project](../resources/project.md)
**Operation ID:** `getProjectVersionsPaginated`

Returns all versions for the specified project. Results are <a href="#pagination">paginated</a>.
 <p>
 Results can be ordered by the following fields:
 <ul>
 <li>sequence</li>
 <li>name</li>
 <li>startDate</li>
 <li>releaseDate</li>
 </ul>
 </p>

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `startAt` | query | integer (int64) | No | the page offset, if not specified then defaults to 0 |
| `maxResults` | query | integer (int32) | No | how many results on the page should be included. Defaults to 50. |
| `orderBy` | query | string | No | ordering of the results. |
| `expand` | query | string | No | the parameters to expand |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful Response |

