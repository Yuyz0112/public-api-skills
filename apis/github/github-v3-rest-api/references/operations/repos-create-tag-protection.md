# POST /repos/{owner}/{repo}/tags/protection

**Resource:** [repos](../resources/repos.md)
**Closing down - Create a tag protection state for a repository**
**Operation ID:** `repos/create-tag-protection`
⚠️ **Deprecated**

> [!WARNING]
> **Closing down notice:** This operation is closing down and will be removed after August 30, 2024. Use the "[Repository Rulesets](https://docs.github.com/rest/repos/rules#create-a-repository-ruleset)" endpoint instead.

This creates a tag protection state for a repository.
This endpoint is only available to repository administrators.

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 201 | Response |
| 403 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

[tag-protection](../schemas/tag-protection/tag-protection.md)

