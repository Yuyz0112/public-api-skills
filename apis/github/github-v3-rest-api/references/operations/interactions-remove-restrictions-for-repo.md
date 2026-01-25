# DELETE /repos/{owner}/{repo}/interaction-limits

**Resource:** [interactions](../resources/interactions.md)
**Remove interaction restrictions for a repository**
**Operation ID:** `interactions/remove-restrictions-for-repo`

Removes all interaction restrictions from the given repository. You must have owner or admin access to remove restrictions. If the interaction limit is set for the user or organization that owns this repository, you will receive a `409 Conflict` response and will not be able to use this endpoint to change the interaction limit for a single repository.

## Responses

| Status | Description |
|--------|-------------|
| 204 | Response |
| 409 | Response |

