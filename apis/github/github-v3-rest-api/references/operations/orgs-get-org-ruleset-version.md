# GET /orgs/{org}/rulesets/{ruleset_id}/history/{version_id}

**Resource:** [orgs](../resources/orgs.md)
**Get organization ruleset version**
**Operation ID:** `orgs/get-org-ruleset-version`

Get a version of an organization ruleset.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `ruleset_id` | path | integer | Yes | The ID of the ruleset. |
| `version_id` | path | integer | Yes | The ID of the version |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 404 | (reference) |
| 500 | (reference) |

**Success Response Schema:**

[ruleset-version-with-state](../schemas/ruleset-version-with-state/ruleset-version-with-state.md)

