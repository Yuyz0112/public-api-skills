# SearchResults

The result of a JQL search.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `expand` | string | No | Expand options that include additional search result details in the response. |
| `issues` | IssueBean[] | No | The list of issues found by the search. |
| `maxResults` | integer (int32) | No | The maximum number of results that could be on the page. |
| `names` | object | No | The ID and name of each field in the search results. |
| `schema` | object | No | The schema describing the field types in the search results. |
| `startAt` | integer (int32) | No | The index of the first item returned on the page. |
| `total` | integer (int32) | No | The number of results on the page. |
| `warningMessages` | string[] | No | Any warnings related to the JQL query. |

