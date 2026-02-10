# GET /api/v4/namespaces

**Resource:** [Namespaces](../resources/Namespaces.md)
**List namespaces**
**Operation ID:** `getApiV4Namespaces`

Get a list of the namespaces of the authenticated user. If the user is an administrator, a list of all namespaces in the GitLab instance is shown.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `search` | query | string | No | Returns a list of namespaces the user is authorized to view based on the search criteria |
| `owned_only` | query | boolean | No | In GitLab 14.2 and later, returns a list of owned namespaces only |
| `top_level_only` | query | boolean | No | Only include top level namespaces |
| `full_path_search` | query | boolean | No | If `true`, the `search` parameter is matched against the full path of the namespaces |
| `page` | query | integer | No | Current page number |
| `per_page` | query | integer | No | Number of items per page |
| `requested_hosted_plan` | query | string | No | Name of the hosted plan requested by the customer |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 401 | Unauthorized |

**Success Response Schema:**

[APIEntitiesNamespace](../schemas/APIEntitiesNamespace/APIEntitiesNamespace.md)

