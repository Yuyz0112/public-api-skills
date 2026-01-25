# GET /accounts/{account_id}/r2-catalog/{bucket_name}/namespaces

**Resource:** [Namespace Management](../resources/Namespace-Management.md)
**List namespaces in catalog**
**Operation ID:** `list-namespaces`

Returns a list of namespaces in the specified R2 catalog.
Supports hierarchical filtering and pagination for efficient traversal
of large namespace hierarchies.


## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | r2-data-catalog_account-id | Yes | Identifies the account. |
| `bucket_name` | path | r2-data-catalog_bucket-name | Yes | Specifies the R2 bucket name. |
| `page_token` | query | string | No | Opaque pagination token from a previous response.
Use this to fetch the next page of results.
 |
| `page_size` | query | integer | No | Maximum number of namespaces to return per page.
Defaults to 100, maximum 1000.
 |
| `parent` | query | string | No | Parent namespace to filter by. Only returns direct children of this namespace.
For nested namespaces, use %1F as separator (e.g., "bronze%1Fanalytics").
Omit this parameter to list top-level namespaces.
 |
| `return_uuids` | query | boolean | No | Whether to include namespace UUIDs in the response.
Set to true to receive the namespace_uuids array.
 |
| `return_details` | query | boolean | No | Whether to include additional metadata (timestamps).
When true, response includes created_at and updated_at arrays.
 |

## Responses

| Status | Description |
|--------|-------------|
| 200 | List of namespaces retrieved successfully. |
| 400 | Bad request (e.g., invalid page_size, malformed parent namespace). |
| 401 | Authentication failed. |
| 403 | Forbidden. |
| 404 | Catalog not found. |
| 500 | Internal server error. |

## Security

- **api_token**
- **api_email**
- **api_key**
