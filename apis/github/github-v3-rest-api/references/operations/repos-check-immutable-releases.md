# GET /repos/{owner}/{repo}/immutable-releases

**Resource:** [repos](../resources/repos.md)
**Check if immutable releases are enabled for a repository**
**Operation ID:** `repos/check-immutable-releases`

Shows whether immutable releases are enabled or disabled. Also identifies whether immutability is being
enforced by the repository owner.  The authenticated user must have admin read access to the repository.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response if immutable releases are enabled |
| 404 | Not Found if immutable releases are not enabled for the repository |

**Success Response Schema:**

[check-immutable-releases](../schemas/check-immutable-releases/check-immutable-releases.md)

