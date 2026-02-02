# GET /password/policy

**Resource:** [password](../resources/password.md)
**Operation ID:** `getPasswordPolicy`

Returns the list of requirements for the current password policy. For example, "The password must have at least 10 characters.",
 "The password must not be similar to the user's name or email address.", etc.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `hasOldPassword` | query | boolean | No | whether or not the user will be required to enter their current password.  Use
                       {@code false} (the default) if this is a new user or if an administrator is forcibly changing
                       another user's password. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful Response |

