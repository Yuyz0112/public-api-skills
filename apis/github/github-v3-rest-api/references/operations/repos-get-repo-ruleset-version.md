# GET /repos/{owner}/{repo}/rulesets/{ruleset_id}/history/{version_id}

**Resource:** [repos](../resources/repos.md)
**Get repository ruleset version**
**Operation ID:** `repos/get-repo-ruleset-version`

Get a version of a repository ruleset.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `ruleset_id` | path | integer | Yes | The ID of the ruleset. |
| `version_id` | path | integer | Yes | The ID of the version |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 404 | (reference) |
| 500 | (reference) |

**Success Response Schema:**

[ruleset-version-with-state](../schemas/ruleset-version-with-state/ruleset-version-with-state.md)

