# GET /api/v4/users/{id}/custom_attributes/{key}

**Resource:** [Custom attributes](../resources/Custom-attributes.md)
**Get a custom attribute on a user**
**Operation ID:** `getApiV4UsersIdCustomAttributesKey`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `key` | path | string | Yes | The key of the custom attribute |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

**Success Response Schema:**

[APIEntitiesCustomAttribute](../schemas/APIEntitiesCustomAttribute/APIEntitiesCustomAttribute.md)

