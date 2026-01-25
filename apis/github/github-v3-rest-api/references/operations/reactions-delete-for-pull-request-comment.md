# DELETE /repos/{owner}/{repo}/pulls/comments/{comment_id}/reactions/{reaction_id}

**Resource:** [reactions](../resources/reactions.md)
**Delete a pull request comment reaction**
**Operation ID:** `reactions/delete-for-pull-request-comment`

> [!NOTE]
> You can also specify a repository by `repository_id` using the route `DELETE /repositories/:repository_id/pulls/comments/:comment_id/reactions/:reaction_id.`

Delete a reaction to a [pull request review comment](https://docs.github.com/rest/pulls/comments#get-a-review-comment-for-a-pull-request).

## Responses

| Status | Description |
|--------|-------------|
| 204 | Response |

