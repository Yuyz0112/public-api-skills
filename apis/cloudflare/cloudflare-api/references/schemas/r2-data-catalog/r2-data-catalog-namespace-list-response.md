# r2-data-catalog_namespace-list-response

Contains the list of namespaces with optional pagination.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `details` | r2-data-catalog_namespace-details[] | No | Contains detailed metadata for each namespace when return_details is true.
Each object includes the namespace, UUID, and timestamps.
 |
| `namespace_uuids` | string[] | No | Contains UUIDs for each namespace when return_uuids is true.
The order corresponds to the namespaces array.
 |
| `namespaces` | r2-data-catalog_namespace-identifier[] | Yes | Lists namespaces in the catalog. |
| `next_page_token` | string | No | Use this opaque token to fetch the next page of results.
A null or absent value indicates the last page.
 |

