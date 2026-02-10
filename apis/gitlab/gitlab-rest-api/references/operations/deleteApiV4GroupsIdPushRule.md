# DELETE /api/v4/groups/{id}/push_rule

**Resource:** [Push rules](../resources/Push-rules.md)
**Deletes group push rule**
**Operation ID:** `deleteApiV4GroupsIdPushRule`

This feature was introduced in GitLab 13.4.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes | The ID or URL-encoded path of a group |

## Responses

| Status | Description |
|--------|-------------|
| 204 | No Content |
| 400 | Validation error |
| 404 | Not found |

