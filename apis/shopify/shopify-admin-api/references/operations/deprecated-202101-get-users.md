# GET /admin/api/2021-01/users.json

**Resource:** [plus/user](../resources/plus-user.md)
**Retrieves a list of all users. Note: As of version 2021-01, this endpoint implements pagination by using links that are provided in the response header. Sending the page parameter will return an error. To learn more, see Making requests to paginated REST Admin API endpoints.**
**Operation ID:** `deprecated_202101_get_users`

https://shopify.dev/docs/admin-api/rest/reference/plus/user#index-2021-01

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `limit` | query | any | No | The maximum number of results to show on a page.
                  (default: 50, maximum: 250) |
| `page_info` | query | any | No | A unique ID used to access a certain page of results. |

## Responses

| Status | Description |
|--------|-------------|
| 200 |  |

