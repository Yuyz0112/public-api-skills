# POST /repos/{owner}/{repo}/keys

**Resource:** [repos](../resources/repos.md)
**Create a deploy key**
**Operation ID:** `repos/create-deploy-key`

You can create a read-only deploy key.

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 201 | Response |
| 422 | (reference) |

**Success Response Schema:**

[deploy-key](../schemas/deploy-key/deploy-key.md)

