# POST /api/v4/groups/{id}/transfer_to_organization

**Resource:** [Groups](../resources/Groups.md)
**Transfer a group to an organization**
**Operation ID:** `postApiV4GroupsIdTransferToOrganization`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes | The ID of a group |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 201 | Created |
| 400 | Bad request |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Group or Organization not found |
| 422 | Unprocessable entity |

**Success Response Schema:**

[APIEntitiesGroupDetail](../schemas/APIEntitiesGroupDetail/APIEntitiesGroupDetail.md)

