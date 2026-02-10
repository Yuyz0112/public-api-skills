# PUT /api/v4/license/{id}/refresh_billable_users

**Resource:** [Licenses](../resources/Licenses.md)
**Refresh licence billable users**
**Operation ID:** `putApiV4LicenseIdRefreshBillableUsers`

Triggers refresh of billable users count for licence

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | integer | Yes | ID of the GitLab license |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not found |

**Success Response Schema:**

[APIEntitiesBasicSuccess](../schemas/APIEntitiesBasicSuccess/APIEntitiesBasicSuccess.md)

