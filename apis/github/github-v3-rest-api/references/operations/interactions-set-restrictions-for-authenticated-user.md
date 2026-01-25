# PUT /user/interaction-limits

**Resource:** [interactions](../resources/interactions.md)
**Set interaction restrictions for your public repositories**
**Operation ID:** `interactions/set-restrictions-for-authenticated-user`

Temporarily restricts which type of GitHub user can interact with your public repositories. Setting the interaction limit at the user level will overwrite any interaction limits that are set for individual repositories owned by the user.

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [interaction-limit](../schemas/interaction-limit/interaction-limit.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 422 | (reference) |

**Success Response Schema:**

[interaction-limit-response](../schemas/interaction-limit-response/interaction-limit-response.md)

