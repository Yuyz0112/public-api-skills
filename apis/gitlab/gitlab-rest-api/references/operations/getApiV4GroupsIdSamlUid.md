# GET /api/v4/groups/{id}/saml/{uid}

**Resource:** [Provider identities](../resources/Provider-identities.md)
**Get a single identity for a user**
**Operation ID:** `getApiV4GroupsIdSamlUid`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes | The ID of a group |
| `uid` | path | string | Yes | External UID of the user |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

**Success Response Schema:**

[APIEntitiesIdentityDetail](../schemas/APIEntitiesIdentityDetail/APIEntitiesIdentityDetail.md)

