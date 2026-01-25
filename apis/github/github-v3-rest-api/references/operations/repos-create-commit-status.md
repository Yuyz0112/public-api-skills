# POST /repos/{owner}/{repo}/statuses/{sha}

**Resource:** [repos](../resources/repos.md)
**Create a commit status**
**Operation ID:** `repos/create-commit-status`

Users with push access in a repository can create commit statuses for a given SHA.

Note: there is a limit of 1000 statuses per `sha` and `context` within a repository. Attempts to create more than 1000 statuses will result in a validation error.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `sha` | path | string | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 201 | Response |

**Success Response Schema:**

[status](../schemas/status/status.md)

