# GET /api/v4/personal_access_tokens

**Resource:** [Personal access tokens](../resources/Personal-access-tokens.md)
**List personal access tokens**
**Operation ID:** `getApiV4PersonalAccessTokens`

Get all personal access tokens the authenticated user has access to.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `user_id` | query | integer | No | Filter PATs by User ID |
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
| `page` | query | integer | No | Current page number |
| `per_page` | query | integer | No | Number of items per page |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 401 | Unauthorized |

**Success Response Schema:**

[APIEntitiesPersonalAccessTokenWithLastUsedIps](../schemas/APIEntitiesPersonalAccessTokenWithLastUsedIps/APIEntitiesPersonalAccessTokenWithLastUsedIps.md)

