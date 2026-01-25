# POST /orgs/{org}/rulesets

**Resource:** [repos](../resources/repos.md)
**Create an organization repository ruleset**
**Operation ID:** `repos/create-org-ruleset`

Create a repository ruleset for an organization.

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

