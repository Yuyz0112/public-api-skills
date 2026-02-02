# GET /issue/{issueIdOrKey}/comment

**Resource:** [issue](../resources/issue.md)
**Operation ID:** `getComments`

Returns all comments for an issue.
 <p>
 Results can be ordered by the "created" field which means the date a comment was added.
 </p>

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `startAt` | query | integer (int64) | No | the page offset, if not specified then defaults to 0 |
| `maxResults` | query | integer (int32) | No | how many results on the page should be included. Defaults to 50. |
| `orderBy` | query | string | No | ordering of the results. |
| `expand` | query | string | No | optional flags: renderedBody (provides body rendered in HTML) |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful Response |

