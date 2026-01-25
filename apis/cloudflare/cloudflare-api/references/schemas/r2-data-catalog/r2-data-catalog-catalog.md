# r2-data-catalog_catalog

Contains R2 Data Catalog information.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `bucket` | string | Yes | Specifies the associated R2 bucket name. |
| `credential_status` | string | No | Shows the credential configuration status. |
| `id` | string (uuid) | Yes | Use this to uniquely identify the catalog. |
| `maintenance_config` | object | No | Configures maintenance for the catalog. |
| `name` | string | Yes | Specifies the catalog name (generated from account and bucket name). |
| `status` | [r2-data-catalog_catalog-status](r2-data-catalog-catalog-status.md) | Yes |  |

