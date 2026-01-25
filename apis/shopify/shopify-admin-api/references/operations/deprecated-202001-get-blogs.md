# GET /admin/api/2020-01/blogs.json

**Resource:** [online-store/blog](../resources/online-store-blog.md)
**Retrieve a list of all blogs. Note: As of version 2019-10, this endpoint implements pagination by using links that are provided in the response header. Sending the page parameter will return an error. To learn more, see Making requests to paginated REST Admin API endpoints.**
**Operation ID:** `deprecated_202001_get_blogs`

https://shopify.dev/docs/admin-api/rest/reference/online-store/blog#index-2020-01

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `limit` | query | any | No | The maximum number of results to retrieve.
                  (default: 50, maximum: 250) |
| `since_id` | query | any | No | Restrict results to after the specified ID |
| `handle` | query | any | No | Filter by blog handle |
| `fields` | query | any | No | comma-separated list of fields to include in the response |

## Responses

| Status | Description |
|--------|-------------|
| 200 |  |

