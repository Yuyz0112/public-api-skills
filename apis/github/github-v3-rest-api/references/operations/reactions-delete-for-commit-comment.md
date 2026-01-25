# DELETE /repos/{owner}/{repo}/comments/{comment_id}/reactions/{reaction_id}

**Resource:** [reactions](../resources/reactions.md)
**Delete a commit comment reaction**
**Operation ID:** `reactions/delete-for-commit-comment`

> [!NOTE]
> You can also specify a repository by `repository_id` using the route `DELETE /repositories/:repository_id/comments/:comment_id/reactions/:reaction_id`.

Delete a reaction to a [commit comment](https://docs.github.com/rest/commits/comments#get-a-commit-comment).

## Responses

| Status | Description |
|--------|-------------|
| 204 | Response |

