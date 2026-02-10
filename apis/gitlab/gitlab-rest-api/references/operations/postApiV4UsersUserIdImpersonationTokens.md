# POST /api/v4/users/{user_id}/impersonation_tokens

**Resource:** [Impersonation tokens](../resources/Impersonation-tokens.md)
**Create a impersonation token. Available only for admins.**
**Operation ID:** `postApiV4UsersUserIdImpersonationTokens`

This feature was introduced in GitLab 9.0

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `user_id` | path | integer | Yes | The ID of the user |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 201 | Created |

**Success Response Schema:**

[APIEntitiesImpersonationTokenWithToken](../schemas/APIEntitiesImpersonationTokenWithToken/APIEntitiesImpersonationTokenWithToken.md)

