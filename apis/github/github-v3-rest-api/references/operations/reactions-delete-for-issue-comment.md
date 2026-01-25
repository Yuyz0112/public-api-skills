# DELETE /repos/{owner}/{repo}/issues/comments/{comment_id}/reactions/{reaction_id}

**Resource:** [reactions](../resources/reactions.md)
**Delete an issue comment reaction**
**Operation ID:** `reactions/delete-for-issue-comment`

> [!NOTE]
> You can also specify a repository by `repository_id` using the route `DELETE delete /repositories/:repository_id/issues/comments/:comment_id/reactions/:reaction_id`.

Delete a reaction to an [issue comment](https://docs.github.com/rest/issues/comments#get-an-issue-comment).

## Responses

| Status | Description |
|--------|-------------|
| 204 | Response |

