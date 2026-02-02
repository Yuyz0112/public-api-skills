# GET /search

**Resource:** [search](../resources/search.md)
**Operation ID:** `search`

Searches for issues using JQL.
 <p>
 <b>Sorting</b>
 the <code>jql</code> parameter is a full <a href="http://confluence.atlassian.com/display/JIRA/Advanced+Searching">JQL</a>
 expression, and includes an <code>ORDER BY</code> clause.
 </p>
 <p>
 The <code>fields</code> param (which can be specified multiple times) gives a comma-separated list of fields
 to include in the response. This can be used to retrieve a subset of fields.
 A particular field can be excluded by prefixing it with a minus.
 <p>
 By default, only navigable (<code>*navigable</code>) fields are returned in this search resource. Note: the default is different
 in the get-issue resource -- the default there all fields (<code>*all</code>).
 <ul>
 <li><code>*all</code> - include all fields</li>
 <li><code>*navigable</code> - include just navigable fields</li>
 <li><code>summary,comment</code> - include just the summary and comments</li>
 <li><code>-description</code> - include navigable fields except the description (the default is <code>*navigable</code> for search)</li>
 <li><code>*all,-comment</code> - include everything except comments</li>
 </ul>
 <p>
 </p>
 <p><b>GET vs POST:</b>
 If the JQL query is too large to be encoded as a query param you should instead
 POST to this resource.
 </p>
 <p>
 <b>Expanding Issues in the Search Result:</b>
 It is possible to expand the issues returned by directly specifying the expansion on the expand parameter passed
 in to this resources.
 </p>
 <p>
 For instance, to expand the &quot;changelog&quot; for all the issues on the search result, it is neccesary to
 specify &quot;changelog&quot; as one of the values to expand.
 </p>

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `jql` | query | string | No | a JQL query string |
| `startAt` | query | integer (int32) | No | the index of the first issue to return (0-based) |
| `maxResults` | query | integer (int32) | No | the maximum number of issues to return (defaults to 50). The maximum allowable value is
                      dictated by the Jira property 'jira.search.views.default.max'. If you specify a value that is higher than this
                      number, your search results will be truncated. |
| `validateQuery` | query | boolean | No | whether to validate the JQL query |
| `fields` | query | string | No | the list of fields to return for each issue. By default, all navigable fields are returned. |
| `expand` | query | string | No | A comma-separated list of the parameters to expand. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful Response |

