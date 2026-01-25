# DELETE /repos/{owner}/{repo}/rulesets/{ruleset_id}

**Resource:** [repos](../resources/repos.md)
**Delete a repository ruleset**
**Operation ID:** `repos/delete-repo-ruleset`

Delete a ruleset for a repository.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `ruleset_id` | path | integer | Yes | The ID of the ruleset. |

## Responses

| Status | Description |
|--------|-------------|
| 204 | Response |
| 404 | (reference) |
| 500 | (reference) |

