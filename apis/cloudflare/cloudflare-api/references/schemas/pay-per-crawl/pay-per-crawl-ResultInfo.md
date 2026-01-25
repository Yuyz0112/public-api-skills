# pay-per-crawl_ResultInfo

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `count` | integer | No |  |
| `page` | integer | No |  |
| `per_page` | integer | No |  |
| `total_count` | integer | No |  |
| `total_pages` | integer | No | TotalPages is a pointer so that if TotalPages == 0 we return that there
are indeed 0 pages. omitempty would have removed the field otherwise.
This is important as a customer may be relying on always reading this
property and it should not be absent just because it is 0, only absent
if a value is never provided. |

