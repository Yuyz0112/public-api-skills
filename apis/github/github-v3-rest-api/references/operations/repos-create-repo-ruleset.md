# POST /repos/{owner}/{repo}/rulesets

**Resource:** [repos](../resources/repos.md)
**Create a repository ruleset**
**Operation ID:** `repos/create-repo-ruleset`

Create a ruleset for a repository.

## Request Body

Request body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 201 | Response |
| 404 | (reference) |
| 500 | (reference) |

**Success Response Schema:**

[repository-ruleset](../schemas/repository-ruleset/repository-ruleset.md)

