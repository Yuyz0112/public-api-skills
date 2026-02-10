# PATCH /api/v4/groups/{id}/saml/{uid}

**Resource:** [Provider identities](../resources/Provider-identities.md)
**Update extern_uid for the user**
**Operation ID:** `patchApiV4GroupsIdSamlUid`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes | The ID of a group |
| `uid` | path | string | Yes | Current external UID of the user |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

**Success Response Schema:**

[APIEntitiesIdentityDetail](../schemas/APIEntitiesIdentityDetail/APIEntitiesIdentityDetail.md)

