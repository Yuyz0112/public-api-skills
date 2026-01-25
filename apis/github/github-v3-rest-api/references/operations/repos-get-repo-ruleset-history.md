# GET /repos/{owner}/{repo}/rulesets/{ruleset_id}/history

**Resource:** [repos](../resources/repos.md)
**Get repository ruleset history**
**Operation ID:** `repos/get-repo-ruleset-history`

Get the history of a repository ruleset.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `ruleset_id` | path | integer | Yes | The ID of the ruleset. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 404 | (reference) |
| 500 | (reference) |

**Success Response Schema:**

Array of [ruleset-version](../schemas/ruleset-version/ruleset-version.md)

