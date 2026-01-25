# cloudforce-one-requests_request-message-list

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `after` | any | No | Retrieve mes  ges created after this time. |
| `before` | any | No | Retrieve messages created before this time. |
| `page` | integer | Yes | Page number of results. |
| `per_page` | integer | Yes | Number of results per page. |
| `sort_by` | string | No | Field to sort results by. |
| `sort_order` | enum: asc, desc | No | Sort order (asc or desc). |

