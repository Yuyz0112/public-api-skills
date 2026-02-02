# GET /dashboard

**Resource:** [dashboard](../resources/dashboard.md)
**Operation ID:** `list`

Returns a list of all dashboards, optionally filtering them.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `filter` | query | string | No | an optional filter that is applied to the list of dashboards. Valid values include
                        <code>"favourite"</code> for returning only favourite dashboards, and <code>"my"</code> for returning
                        dashboards that are owned by the calling user. |
| `startAt` | query | integer (int32) | No | the index of the first dashboard to return (0-based). must be 0 or a multiple of
                        <code>maxResults</code> |
| `maxResults` | query | integer (int32) | No | a hint as to the maximum number of dashboards to return in each call. Note that the
                        Jira server reserves the right to impose a <code>maxResults</code> limit that is lower than the value that a
                        client provides, dues to lack of resources or any other condition. When this happens, your results will be
                        truncated. Callers should always check the returned <code>maxResults</code> to determine the value that is
                        effectively being used. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful Response |

