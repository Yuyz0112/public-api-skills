# DELETE /repos/{owner}/{repo}/tags/protection/{tag_protection_id}

**Resource:** [repos](../resources/repos.md)
**Closing down - Delete a tag protection state for a repository**
**Operation ID:** `repos/delete-tag-protection`
⚠️ **Deprecated**

> [!WARNING]
> **Closing down notice:** This operation is closing down and will be removed after August 30, 2024. Use the "[Repository Rulesets](https://docs.github.com/rest/repos/rules#delete-a-repository-ruleset)" endpoint instead.

This deletes a tag protection state for a repository.
This endpoint is only available to repository administrators.

## Responses

| Status | Description |
|--------|-------------|
| 204 | Response |
| 403 | (reference) |
| 404 | (reference) |

