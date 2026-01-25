# GET /rest/api/3/label

**Resource:** [Labels](../resources/Labels.md)
**Get all labels**
**Operation ID:** `getAllLabels`

Returns a [paginated](#pagination) list of labels.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `startAt` | query | integer (int64) | No | The index of the first item to return in a page of results (page offset). |
| `maxResults` | query | integer (int32) | No | The maximum number of items to return per page. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |

**Success Response Schema:**

[PageBeanString](../schemas/Page/PageBeanString.md)

## Security

- **basicAuth**
- **OAuth2**: read:jira-work
