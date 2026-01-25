# r2-data-catalog Schemas

34 schemas in this group.

| Schema | Type | Description |
|--------|------|-------------|
| [r2-data-catalog_account-id](r2-data-catalog-account-id.md) | primitive | Use this to identify the account. |
| [r2-data-catalog_api-response-collection](r2-data-catalog-api-response-collection.md) | allOf |  |
| [r2-data-catalog_api-response-common-failure](r2-data-catalog-api-response-common-failure.md) | object |  |
| [r2-data-catalog_api-response-errors](r2-data-catalog-api-response-errors.md) | array | Contains errors if the API call was unsuccessful. |
| [r2-data-catalog_api-response-messages](r2-data-catalog-api-response-messages.md) | array | Contains informational messages. |
| [r2-data-catalog_api-response-single](r2-data-catalog-api-response-single.md) | object |  |
| [r2-data-catalog_api-response-success](r2-data-catalog-api-response-success.md) | primitive | Indicates whether the API call was successful. |
| [r2-data-catalog_bucket-name](r2-data-catalog-bucket-name.md) | primitive | Specifies the R2 bucket name. |
| [r2-data-catalog_catalog](r2-data-catalog-catalog.md) | object | Contains R2 Data Catalog information. |
| [r2-data-catalog_catalog-activation-response](r2-data-catalog-catalog-activation-response.md) | object | Contains response from activating an R2 bucket as  |
| [r2-data-catalog_catalog-compaction-config](r2-data-catalog-catalog-compaction-config.md) | object | Configures compaction for catalog maintenance. |
| [r2-data-catalog_catalog-credential-request](r2-data-catalog-catalog-credential-request.md) | object | Contains request to store catalog credentials. |
| [r2-data-catalog_catalog-list](r2-data-catalog-catalog-list.md) | object | Contains the list of catalogs. |
| [r2-data-catalog_catalog-maintenance-config](r2-data-catalog-catalog-maintenance-config.md) | object | Configures maintenance for the catalog. |
| [r2-data-catalog_catalog-maintenance-config-response](r2-data-catalog-catalog-maintenance-config-response.md) | object | Contains maintenance configuration and credential  |
| [r2-data-catalog_catalog-maintenance-state](r2-data-catalog-catalog-maintenance-state.md) | enum | Specifies the state of maintenance operations. |
| [r2-data-catalog_catalog-maintenance-update-request](r2-data-catalog-catalog-maintenance-update-request.md) | allOf | Contains request to update catalog maintenance con |
| [r2-data-catalog_catalog-status](r2-data-catalog-catalog-status.md) | enum | Indicates the status of the catalog. |
| [r2-data-catalog_catalog-target-file-size](r2-data-catalog-catalog-target-file-size.md) | enum | Sets the target file size for compaction in megaby |
| [r2-data-catalog_compaction-update-params](r2-data-catalog-compaction-update-params.md) | object | Updates compaction configuration (all fields optio |
| [r2-data-catalog_credential-status](r2-data-catalog-credential-status.md) | enum | Shows the credential configuration status. |
| [r2-data-catalog_maintenance-update-params](r2-data-catalog-maintenance-update-params.md) | object | Contains maintenance update parameters. |
| [r2-data-catalog_namespace-details](r2-data-catalog-namespace-details.md) | object | Contains namespace with metadata details. |
| [r2-data-catalog_namespace-identifier](r2-data-catalog-namespace-identifier.md) | array | Specifies the hierarchical namespace parts as an a |
| [r2-data-catalog_namespace-list-response](r2-data-catalog-namespace-list-response.md) | object | Contains the list of namespaces with optional pagi |
| [r2-data-catalog_snapshot-expiration-config](r2-data-catalog-snapshot-expiration-config.md) | object | Configures snapshot expiration settings. |
| [r2-data-catalog_snapshot-expiration-update-params](r2-data-catalog-snapshot-expiration-update-params.md) | object | Updates snapshot expiration configuration (all fie |
| [r2-data-catalog_table-compaction-config](r2-data-catalog-table-compaction-config.md) | object | Configures compaction settings for table optimizat |
| [r2-data-catalog_table-details](r2-data-catalog-table-details.md) | object | Contains table with metadata. |
| [r2-data-catalog_table-identifier](r2-data-catalog-table-identifier.md) | object | Specifies a unique table identifier within a catal |
| [r2-data-catalog_table-list-response](r2-data-catalog-table-list-response.md) | object | Contains the list of tables with optional paginati |
| [r2-data-catalog_table-maintenance-config](r2-data-catalog-table-maintenance-config.md) | object | Configures maintenance for the table. |
| [r2-data-catalog_table-maintenance-config-response](r2-data-catalog-table-maintenance-config-response.md) | object | Contains table maintenance configuration. |
| [r2-data-catalog_table-maintenance-update-request](r2-data-catalog-table-maintenance-update-request.md) | allOf | Contains request to update table maintenance confi |
