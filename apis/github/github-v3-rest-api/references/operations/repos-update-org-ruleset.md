# PUT /orgs/{org}/rulesets/{ruleset_id}

**Resource:** [repos](../resources/repos.md)
**Update an organization repository ruleset**
**Operation ID:** `repos/update-org-ruleset`

Update a ruleset for an organization.

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

