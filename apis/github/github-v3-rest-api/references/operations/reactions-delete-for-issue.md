# DELETE /repos/{owner}/{repo}/issues/{issue_number}/reactions/{reaction_id}

**Resource:** [reactions](../resources/reactions.md)
**Delete an issue reaction**
**Operation ID:** `reactions/delete-for-issue`

> [!NOTE]
> You can also specify a repository by `repository_id` using the route `DELETE /repositories/:repository_id/issues/:issue_number/reactions/:reaction_id`.

Delete a reaction to an [issue](https://docs.github.com/rest/issues/issues#get-an-issue).

## Responses

| Status | Description |
|--------|-------------|
| 204 | Response |

