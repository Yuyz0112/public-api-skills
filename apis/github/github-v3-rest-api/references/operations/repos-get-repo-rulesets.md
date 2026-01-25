# GET /repos/{owner}/{repo}/rulesets

**Resource:** [repos](../resources/repos.md)
**Get all repository rulesets**
**Operation ID:** `repos/get-repo-rulesets`

Get all the rulesets for a repository.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `includes_parents` | query | boolean | No | Include rulesets configured at higher levels that apply to this repository |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 404 | (reference) |
| 500 | (reference) |

**Success Response Schema:**

Array of [repository-ruleset](../schemas/repository-ruleset/repository-ruleset.md)

