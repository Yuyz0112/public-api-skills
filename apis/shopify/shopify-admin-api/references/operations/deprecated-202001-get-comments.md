# GET /admin/api/2020-01/comments.json

**Resource:** [online-store/comment](../resources/online-store-comment.md)
**Retrieves a list of comments. Note: As of version 2019-10, this endpoint implements pagination by using links that are provided in the response header. Sending the page parameter will return an error. To learn more, see Making requests to paginated REST Admin API endpoints.**
**Operation ID:** `deprecated_202001_get_comments`

https://shopify.dev/docs/admin-api/rest/reference/online-store/comment#index-2020-01

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `limit` | query | any | No | The maximum number of results to retrieve.
                  (default: 50, maximum: 250) |
| `since_id` | query | any | No | Restrict results to after the specified ID. |
| `created_at_min` | query | any | No | Show comments created after date (format: 2014-04-25T16:15:47-04:00). |
| `created_at_max` | query | any | No | Show comments created before date (format: 2014-04-25T16:15:47-04:00). |
| `updated_at_min` | query | any | No | Show comments last updated after date (format: 2014-04-25T16:15:47-04:00). |
| `updated_at_max` | query | any | No | Show comments last updated before date (format: 2014-04-25T16:15:47-04:00). |
| `published_at_min` | query | any | No | Show comments published after date (format: 2014-04-25T16:15:47-04:00). |
| `published_at_max` | query | any | No | Show comments published before date (format: 2014-04-25T16:15:47-04:00). |
| `fields` | query | any | No | Show only certain fields, specified by a comma-separated list of field names. |
| `published_status` | query | any | No | Filter results by their published status.
                  (default: any)
                    
                        published: Show only published comments.
                        unpublished: Show only unpublished comments.
                        any: Show comments of any published status. |
| `status` | query | any | No | Filter results by their status.
                    
                        pending: Show only pending comments.
                        published: Show only published comments.
                        unapproved: Show only unapproved comments. |
| `article_id` | query | integer | No | article_id |
| `blog_id` | query | integer | No | blog_id |

## Responses

| Status | Description |
|--------|-------------|
| 200 |  |

