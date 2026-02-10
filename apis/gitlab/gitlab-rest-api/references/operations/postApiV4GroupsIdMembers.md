# POST /api/v4/groups/{id}/members

**Resource:** [Members](../resources/Members.md)
**Adds a member to a group or project.**
**Operation ID:** `postApiV4GroupsIdMembers`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes | The group ID |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 201 | Created |

**Success Response Schema:**

[APIEntitiesMember](../schemas/APIEntitiesMember/APIEntitiesMember.md)

