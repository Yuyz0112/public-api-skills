# PUT /api/v4/groups/{id}/security_settings

**Resource:** [Groups](../resources/Groups.md)
**Update group security settings**
**Operation ID:** `putApiV4GroupsIdSecuritySettings`

Updates secret_push_protection_enabled for all projects to the new value

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the group |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

