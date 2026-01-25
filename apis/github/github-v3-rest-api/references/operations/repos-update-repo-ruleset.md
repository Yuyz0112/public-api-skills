# PUT /repos/{owner}/{repo}/rulesets/{ruleset_id}

**Resource:** [repos](../resources/repos.md)
**Update a repository ruleset**
**Operation ID:** `repos/update-repo-ruleset`

Update a ruleset for a repository.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `ruleset_id` | path | integer | Yes | The ID of the ruleset. |

## Request Body

Request body

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 404 | (reference) |
| 500 | (reference) |

**Success Response Schema:**

[repository-ruleset](../schemas/repository-ruleset/repository-ruleset.md)

