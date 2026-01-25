# r2-data-catalog_table-list-response

Contains the list of tables with optional pagination.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `details` | r2-data-catalog_table-details[] | No | Contains detailed metadata for each table when return_details is true.
Each object includes identifier, UUID, timestamps, and locations.
 |
| `identifiers` | r2-data-catalog_table-identifier[] | Yes | Lists tables in the namespace. |
| `next_page_token` | string | No | Use this opaque token to fetch the next page of results.
A null or absent value indicates the last page.
 |
| `table_uuids` | string[] | No | Contains UUIDs for each table when return_uuids is true.
The order corresponds to the identifiers array.
 |

