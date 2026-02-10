# DELETE /api/v4/users/{id}/emails/{email_id}

**Resource:** [Users](../resources/Users.md)
**Delete an email address of a specified user. Available only for admins.**
**Operation ID:** `deleteApiV4UsersIdEmailsEmailId`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | integer | Yes | The ID of the user |
| `email_id` | path | integer | Yes | The ID of the email |

## Responses

| Status | Description |
|--------|-------------|
| 204 | No Content |

