# GET /repos/{owner}/{repo}/tags/protection

**Resource:** [repos](../resources/repos.md)
**Closing down - List tag protection states for a repository**
**Operation ID:** `repos/list-tag-protection`
⚠️ **Deprecated**

> [!WARNING]
> **Closing down notice:** This operation is closing down and will be removed after August 30, 2024. Use the "[Repository Rulesets](https://docs.github.com/rest/repos/rules#get-all-repository-rulesets)" endpoint instead.

This returns the tag protection states of a repository.

This information is only available to repository administrators.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 403 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

Array of [tag-protection](../schemas/tag-protection/tag-protection.md)

