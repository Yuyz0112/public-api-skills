# GET /api/v4/groups/{id}/manage/ssh_keys

**Resource:** [Group credentials inventory](../resources/Group-credentials-inventory.md)
**Get the ssh_keys for the user belonging to group**
**Operation ID:** `getApiV4GroupsIdManageSshKeys`

This feature was introduced in GitLab 17.9.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `created_before` | query | string (date-time) | No | Filter ssh keys which were created before given datetime |
| `created_after` | query | string (date-time) | No | Filter ssh keys which were created after given datetime |
| `expires_before` | query | string (date-time) | No | Filter ssh keys which expire before given datetime |
| `expires_after` | query | string (date-time) | No | Filter ssh keys which expire after given datetime |
| `page` | query | integer | No | Current page number |
| `per_page` | query | integer | No | Number of items per page |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

**Success Response Schema:**

[APIEntitiesSshKeyWithUserId](../schemas/APIEntitiesSshKeyWithUserId/APIEntitiesSshKeyWithUserId.md)

