# GET /repos/{owner}/{repo}/branches

**Resource:** [repos](../resources/repos.md)
**List branches**
**Operation ID:** `repos/list-branches`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `protected` | query | boolean | No | Setting to `true` returns only branches protected by branch protections or rulesets. When set to `false`, only unprotected branches are returned. Omitting this parameter returns all branches. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 404 | (reference) |

**Success Response Schema:**

Array of [short-branch](../schemas/short-branch/short-branch.md)

