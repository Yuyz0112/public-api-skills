# DELETE /orgs/{org}/rulesets/{ruleset_id}

**Resource:** [repos](../resources/repos.md)
**Delete an organization repository ruleset**
**Operation ID:** `repos/delete-org-ruleset`

Delete a ruleset for an organization.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `ruleset_id` | path | integer | Yes | The ID of the ruleset. |

## Responses

| Status | Description |
|--------|-------------|
| 204 | Response |
| 404 | (reference) |
| 500 | (reference) |

