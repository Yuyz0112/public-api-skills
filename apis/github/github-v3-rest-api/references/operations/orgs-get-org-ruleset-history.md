# GET /orgs/{org}/rulesets/{ruleset_id}/history

**Resource:** [orgs](../resources/orgs.md)
**Get organization ruleset history**
**Operation ID:** `orgs/get-org-ruleset-history`

Get the history of an organization ruleset.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `ruleset_id` | path | integer | Yes | The ID of the ruleset. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 404 | (reference) |
| 500 | (reference) |

**Success Response Schema:**

Array of [ruleset-version](../schemas/ruleset-version/ruleset-version.md)

