# DELETE /api/v4/groups/{id}/saml/{uid}

**Resource:** [Provider identities](../resources/Provider-identities.md)
**Delete the Provider identity**
**Operation ID:** `deleteApiV4GroupsIdSamlUid`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes | The ID of a group |
| `uid` | path | string | Yes | Current external UID of the user |

## Responses

| Status | Description |
|--------|-------------|
| 204 | No Content |

