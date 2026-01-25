# GET /accounts/{account_id}/r2-catalog/{bucket_name}/namespaces/{namespace}/tables

**Resource:** [Table Management](../resources/Table-Management.md)
**List tables in namespace**
**Operation ID:** `list-tables`

Returns a list of tables in the specified namespace within an R2 catalog.
Supports pagination for efficient traversal of large table collections.


## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | r2-data-catalog_account-id | Yes | Identifies the account. |
| `bucket_name` | path | r2-data-catalog_bucket-name | Yes | Specifies the R2 bucket name. |
| `namespace` | path | string | Yes | The namespace identifier.
For nested namespaces, use %1F as separator (e.g., "bronze%1Fanalytics").
 |
| `page_token` | query | string | No | Opaque pagination token from a previous response.
Use this to fetch the next page of results.
 |
| `page_size` | query | integer | No | Maximum number of tables to return per page.
Defaults to 100, maximum 1000.
 |
| `return_uuids` | query | boolean | No | Whether to include table UUIDs in the response.
Set to true to receive the table_uuids array.
 |
| `return_details` | query | boolean | No | Whether to include additional metadata (timestamps, locations).
When true, response includes created_at, updated_at, metadata_locations, and locations arrays.
 |

## Responses

| Status | Description |
|--------|-------------|
| 200 | List of tables retrieved successfully. |
| 400 | Bad request (e.g., invalid page_size, malformed namespace). |
| 401 | Authentication failed. |
| 403 | Forbidden. |
| 404 | Catalog or namespace not found. |
| 500 | Internal server error. |

## Security

- **api_token**
- **api_email**
- **api_key**
