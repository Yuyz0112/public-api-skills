# PUT /repos/{owner}/{repo}/interaction-limits

**Resource:** [interactions](../resources/interactions.md)
**Set interaction restrictions for a repository**
**Operation ID:** `interactions/set-restrictions-for-repo`

Temporarily restricts interactions to a certain type of GitHub user within the given repository. You must have owner or admin access to set these restrictions. If an interaction limit is set for the user or organization that owns this repository, you will receive a `409 Conflict` response and will not be able to use this endpoint to change the interaction limit for a single repository.

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [interaction-limit](../schemas/interaction-limit/interaction-limit.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 409 | Response |

**Success Response Schema:**

[interaction-limit-response](../schemas/interaction-limit-response/interaction-limit-response.md)

