# GET /repos/{owner}/{repo}

**Resource:** [repos](../resources/repos.md)
**Get a repository**
**Operation ID:** `repos/get`

The `parent` and `source` objects are present when the repository is a fork. `parent` is the repository this repository was forked from, `source` is the ultimate source for the network.

> [!NOTE]
> - In order to see the `security_and_analysis` block for a repository you must have admin permissions for the repository or be an owner or security manager for the organization that owns the repository. For more information, see "[Managing security managers in your organization](https://docs.github.com/organizations/managing-peoples-access-to-your-organization-with-roles/managing-security-managers-in-your-organization)."
> - To view merge-related settings, you must have the `contents:read` and `contents:write` permissions.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 301 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

[full-repository](../schemas/full-repository/full-repository.md)

