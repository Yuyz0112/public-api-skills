# GET /api/v4/user/emails

**Resource:** [Users](../resources/Users.md)
**Get the currently authenticated user's email addresses**
**Operation ID:** `getApiV4UserEmails`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `page` | query | integer | No | Current page number |
| `per_page` | query | integer | No | Number of items per page |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

**Success Response Schema:**

[APIEntitiesEmail](../schemas/APIEntitiesEmail/APIEntitiesEmail.md)

