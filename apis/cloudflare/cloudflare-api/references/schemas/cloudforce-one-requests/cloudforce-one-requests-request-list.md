# cloudforce-one-requests_request-list

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `completed_after` | any | No | Retrieve requests completed after this time. |
| `completed_before` | any | No | Retrieve requests completed before this time. |
| `created_after` | any | No | Retrieve requests created after this time. |
| `created_before` | any | No | Retrieve requests created before this time. |
| `page` | integer | Yes | Page number of results. |
| `per_page` | integer | Yes | Number of results per page. |
| `request_type` | [cloudforce-one-requests_request-type](cloudforce-one-requests-request-type.md) | No |  |
| `sort_by` | string | No | Field to sort results by. |
| `sort_order` | enum: asc, desc | No | Sort order (asc or desc). |
| `status` | [cloudforce-one-requests_request-status](cloudforce-one-requests-request-status.md) | No |  |

