# GET /repos/{owner}/{repo}/rulesets/{ruleset_id}

**Resource:** [repos](../resources/repos.md)
**Get a repository ruleset**
**Operation ID:** `repos/get-repo-ruleset`

Get a ruleset for a repository.

**Note:** To prevent leaking sensitive information, the `bypass_actors` property is only returned if the user
making the API request has write access to the ruleset.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `ruleset_id` | path | integer | Yes | The ID of the ruleset. |
| `includes_parents` | query | boolean | No | Include rulesets configured at higher levels that apply to this repository |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 404 | (reference) |
| 500 | (reference) |

**Success Response Schema:**

[repository-ruleset](../schemas/repository-ruleset/repository-ruleset.md)

