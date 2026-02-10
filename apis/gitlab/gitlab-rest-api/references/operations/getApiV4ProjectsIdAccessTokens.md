# GET /api/v4/projects/{id}/access_tokens

**Resource:** [Project access tokens](../resources/Project-access-tokens.md)
**Get list of all access tokens for the specified resource**
**Operation ID:** `getApiV4ProjectsIdAccessTokens`

This feature was introduced in GitLab 13.9.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | ID or URL-encoded path of the project |
| `revoked` | query | boolean | No | Filter tokens where revoked state matches parameter |
| `state` | query | enum: active, inactive | No | Filter tokens which are either active or not |
| `created_before` | query | string (date-time) | No | Filter tokens which were created before given datetime |
| `created_after` | query | string (date-time) | No | Filter tokens which were created after given datetime |
| `last_used_before` | query | string (date-time) | No | Filter tokens which were used before given datetime |
| `last_used_after` | query | string (date-time) | No | Filter tokens which were used after given datetime |
| `expires_before` | query | string (date) | No | Filter tokens which expire before given datetime |
| `expires_after` | query | string (date) | No | Filter tokens which expire after given datetime |
| `search` | query | string | No | Filters tokens by name |
| `sort` | query | string | No | Sort tokens |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

**Success Response Schema:**

[APIEntitiesResourceAccessToken](../schemas/APIEntitiesResourceAccessToken/APIEntitiesResourceAccessToken.md)

