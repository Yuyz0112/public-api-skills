# GET /api/v4/user/emails/{email_id}

**Resource:** [Users](../resources/Users.md)
**Get a single email address owned by the currently authenticated user**
**Operation ID:** `getApiV4UserEmailsEmailId`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `email_id` | path | integer | Yes | The ID of the email |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

**Success Response Schema:**

[APIEntitiesEmail](../schemas/APIEntitiesEmail/APIEntitiesEmail.md)

