# GET /api/v4/users/{user_id}/impersonation_tokens

**Resource:** [Impersonation tokens](../resources/Impersonation-tokens.md)
**Retrieve impersonation tokens. Available only for admins.**
**Operation ID:** `getApiV4UsersUserIdImpersonationTokens`

This feature was introduced in GitLab 9.0

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `user_id` | path | integer | Yes | The ID of the user |
| `page` | query | integer | No | Current page number |
| `per_page` | query | integer | No | Number of items per page |
| `state` | query | enum: all, active, inactive | No | Filters (all|active|inactive) impersonation_tokens |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

**Success Response Schema:**

[APIEntitiesImpersonationToken](../schemas/APIEntitiesImpersonationToken/APIEntitiesImpersonationToken.md)

