# GET /admin/api/2020-10/blogs/{blog_id}/articles/count.json

**Resource:** [online-store/article](../resources/online-store-article.md)
**Retrieves a count of all articles from a blog**
**Operation ID:** `get_blogs_param_blog_id_articles_count`

https://shopify.dev/docs/admin-api/rest/reference/online-store/article#count-2020-10

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `blog_id` | path | string | Yes | blog_id |
| `created_at_min` | query | any | No | Count articles created after date (format: 2014-04-25T16:15:47-04:00). |
| `created_at_max` | query | any | No | Count articles created before date (format: 2014-04-25T16:15:47-04:00). |
| `updated_at_min` | query | any | No | Count articles last updated after date (format: 2014-04-25T16:15:47-04:00). |
| `updated_at_max` | query | any | No | Count articles last updated before date (format: 2014-04-25T16:15:47-04:00). |
| `published_at_min` | query | any | No | Count articles published after date (format: 2014-04-25T16:15:47-04:00). |
| `published_at_max` | query | any | No | Count articles published before date (format: 2014-04-25T16:15:47-04:00). |
| `published_status` | query | any | No | Count articles with a given published status.
                  (default: any)
                    
                        published: Count only published articles.
                        unpublished: Count only unpublished articles.
                        any: Count all articles. |

## Responses

| Status | Description |
|--------|-------------|
| 200 |  |

