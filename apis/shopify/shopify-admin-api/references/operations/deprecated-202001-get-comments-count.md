# GET /admin/api/2020-01/comments/count.json

**Resource:** [online-store/comment](../resources/online-store-comment.md)
**Retrieves a count of comments**
**Operation ID:** `deprecated_202001_get_comments_count`

https://shopify.dev/docs/admin-api/rest/reference/online-store/comment#count-2020-01

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `created_at_min` | query | any | No | Count comments created after date (format: 2014-04-25T16:15:47-04:00). |
| `created_at_max` | query | any | No | Count comments created before date (format: 2014-04-25T16:15:47-04:00). |
| `updated_at_min` | query | any | No | Count comments last updated after date (format: 2014-04-25T16:15:47-04:00). |
| `updated_at_max` | query | any | No | Count comments last updated before date (format: 2014-04-25T16:15:47-04:00). |
| `published_at_min` | query | any | No | Count comments published after date (format: 2014-04-25T16:15:47-04:00). |
| `published_at_max` | query | any | No | Count comments published before date (format: 2014-04-25T16:15:47-04:00). |
| `published_status` | query | any | No | Retrieve a count of comments with a given published status.
                  (default: any)
                    
                        published: Count only published comments.
                        unpublished: Count only unpublished comments.
                        any: Count comments of any published status. |
| `status` | query | any | No | Retrieve a count of comments with a given status.
                    
                        pending: Count pending comments.
                        published: Count published comments.
                        unapproved: Count unapproved comments. |
| `article_id` | query | integer | No | article_id |
| `blog_id` | query | integer | No | blog_id |

## Responses

| Status | Description |
|--------|-------------|
| 200 |  |

