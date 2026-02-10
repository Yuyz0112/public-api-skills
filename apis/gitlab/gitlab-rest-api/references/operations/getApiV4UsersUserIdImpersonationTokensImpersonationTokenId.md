# GET /api/v4/users/{user_id}/impersonation_tokens/{impersonation_token_id}

**Resource:** [Impersonation tokens](../resources/Impersonation-tokens.md)
**Retrieve impersonation token. Available only for admins.**
**Operation ID:** `getApiV4UsersUserIdImpersonationTokensImpersonationTokenId`

This feature was introduced in GitLab 9.0

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `user_id` | path | integer | Yes | The ID of the user |
| `impersonation_token_id` | path | integer | Yes | The ID of the impersonation token |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

**Success Response Schema:**

[APIEntitiesImpersonationToken](../schemas/APIEntitiesImpersonationToken/APIEntitiesImpersonationToken.md)

