# GET /admin/api/2020-01/blogs/{blog_id}/articles.json

**Resource:** [online-store/article](../resources/online-store-article.md)
**Retrieves a list of all articles from a blog. Note: As of version 2019-10, this endpoint implements pagination by using links that are provided in the response header. Sending the page parameter will return an error. To learn more, see Making requests to paginated REST Admin API endpoints.**
**Operation ID:** `deprecated_202001_get_blogs_param_blog_id_articles`

https://shopify.dev/docs/admin-api/rest/reference/online-store/article#index-2020-01

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `blog_id` | path | string | Yes | blog_id |
| `limit` | query | any | No | The maximum number of results to retrieve.
                  (default: 50, maximum: 250) |
| `since_id` | query | any | No | Restrict results to after the specified ID. |
| `created_at_min` | query | any | No | Show articles created after date (format: 2014-04-25T16:15:47-04:00). |
| `created_at_max` | query | any | No | Show articles created before date (format: 2014-04-25T16:15:47-04:00). |
| `updated_at_min` | query | any | No | Show articles last updated after date (format: 2014-04-25T16:15:47-04:00). |
| `updated_at_max` | query | any | No | Show articles last updated before date (format: 2014-04-25T16:15:47-04:00). |
| `published_at_min` | query | any | No | Show articles published after date (format: 2014-04-25T16:15:47-04:00). |
| `published_at_max` | query | any | No | Show articles published before date (format: 2014-04-25T16:15:47-04:00). |
| `published_status` | query | any | No | Retrieve results based on their published status.
                  (default: any)
                    
                        published: Show only published articles.
                        unpublished: Show only unpublished articles.
                        any: Show articles of any published status. |
| `handle` | query | any | No | Retrieve an article with a specific handle. |
| `tag` | query | any | No | Filter articles with a specific tag. |
| `author` | query | any | No | Filter articles by article author. |
| `fields` | query | any | No | Show only certain fields, specified by a comma-separated list of field names. |

## Responses

| Status | Description |
|--------|-------------|
| 200 |  |

