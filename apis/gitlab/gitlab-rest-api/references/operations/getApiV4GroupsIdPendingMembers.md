# GET /api/v4/groups/{id}/pending_members

**Resource:** [Members](../resources/Members.md)
**Lists all pending members for a group including invited users**
**Operation ID:** `getApiV4GroupsIdPendingMembers`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes | The ID of a group |
| `page` | query | integer | No | Current page number |
| `per_page` | query | integer | No | Number of items per page |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

