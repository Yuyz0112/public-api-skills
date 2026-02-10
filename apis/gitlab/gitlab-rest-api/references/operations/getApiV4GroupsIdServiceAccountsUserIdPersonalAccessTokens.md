# GET /api/v4/groups/{id}/service_accounts/{user_id}/personal_access_tokens

**Resource:** [Personal access tokens](../resources/Personal-access-tokens.md)
**Get a list of all personal access tokens**
**Operation ID:** `getApiV4GroupsIdServiceAccountsUserIdPersonalAccessTokens`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the group |
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
| 400 | Bad Request |
| 401 | 401 Unauthorized |
| 403 | Forbidden |
| 404 | 404 Group Not Found |

**Success Response Schema:**

[APIEntitiesPersonalAccessToken](../schemas/APIEntitiesPersonalAccessToken/APIEntitiesPersonalAccessToken.md)

