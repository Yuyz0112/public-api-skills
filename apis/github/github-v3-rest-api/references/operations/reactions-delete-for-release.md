# DELETE /repos/{owner}/{repo}/releases/{release_id}/reactions/{reaction_id}

**Resource:** [reactions](../resources/reactions.md)
**Delete a release reaction**
**Operation ID:** `reactions/delete-for-release`

> [!NOTE]
> You can also specify a repository by `repository_id` using the route `DELETE delete /repositories/:repository_id/releases/:release_id/reactions/:reaction_id`.

Delete a reaction to a [release](https://docs.github.com/rest/releases/releases#get-a-release).

## Responses

| Status | Description |
|--------|-------------|
| 204 | Response |

