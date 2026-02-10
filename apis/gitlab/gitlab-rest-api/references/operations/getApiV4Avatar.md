# GET /api/v4/avatar

**Resource:** [Avatars](../resources/Avatars.md)
**Return avatar url for a user**
**Operation ID:** `getApiV4Avatar`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `email` | query | string | Yes | Public email address of the user |
| `size` | query | integer | No | Single pixel dimension for Gravatar images |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

**Success Response Schema:**

[APIEntitiesAvatar](../schemas/APIEntitiesAvatar/APIEntitiesAvatar.md)

