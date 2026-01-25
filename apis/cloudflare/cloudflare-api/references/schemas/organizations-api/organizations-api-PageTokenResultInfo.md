# organizations-api_PageTokenResultInfo

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `next_page_token` | string | No | Use this opaque token in the next request to retrieve the
next page.

Parameters used to filter the retrieved list must remain in subsequent
requests with a page token. |
| `total_size` | integer | No | Counts the total amount of items in a list with the applied filters. The API omits next_page_token to indicate no more items in a particular list. |

