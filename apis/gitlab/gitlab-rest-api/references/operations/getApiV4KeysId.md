# GET /api/v4/keys/{id}

**Resource:** [Keys](../resources/Keys.md)
**Get single ssh key by id. Only available to admin users**
**Operation ID:** `getApiV4KeysId`

Get SSH key with user by ID of an SSH key. Note only administrators can lookup SSH key with user by ID\
        of an SSH key

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID of an SSH key |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

**Success Response Schema:**

[APIEntitiesSSHKeyWithUser](../schemas/APIEntitiesSSHKeyWithUser/APIEntitiesSSHKeyWithUser.md)

