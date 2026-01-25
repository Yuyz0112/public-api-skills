# PUT /orgs/{org}/interaction-limits

**Resource:** [interactions](../resources/interactions.md)
**Set interaction restrictions for an organization**
**Operation ID:** `interactions/set-restrictions-for-org`

Temporarily restricts interactions to a certain type of GitHub user in any public repository in the given organization. You must be an organization owner to set these restrictions. Setting the interaction limit at the organization level will overwrite any interaction limits that are set for individual repositories owned by the organization.

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

