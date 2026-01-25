# workers-kv Schemas

26 schemas in this group.

| Schema | Type | Description |
|--------|------|-------------|
| [workers-kv_any](workers-kv-any.md) | anyOf |  |
| [workers-kv_api-response-collection](workers-kv-api-response-collection.md) | allOf |  |
| [workers-kv_api-response-common](workers-kv-api-response-common.md) | object |  |
| [workers-kv_api-response-common-failure](workers-kv-api-response-common-failure.md) | object |  |
| [workers-kv_api-response-common-no-result](workers-kv-api-response-common-no-result.md) | allOf |  |
| [workers-kv_bulk-get-result](workers-kv-bulk-get-result.md) | object |  |
| [workers-kv_bulk-get-result-with-metadata](workers-kv-bulk-get-result-with-metadata.md) | object |  |
| [workers-kv_bulk-result](workers-kv-bulk-result.md) | object |  |
| [workers-kv_bulk_delete](workers-kv-bulk-delete.md) | array |  |
| [workers-kv_bulk_write](workers-kv-bulk-write.md) | array |  |
| [workers-kv_create_rename_namespace_body](workers-kv-create-rename-namespace-body.md) | object |  |
| [workers-kv_cursor](workers-kv-cursor.md) | primitive | Opaque token indicating the position from which to |
| [workers-kv_expiration](workers-kv-expiration.md) | primitive | Expires the key at a certain time, measured in num |
| [workers-kv_expiration_ttl](workers-kv-expiration-ttl.md) | primitive | Expires the key after a number of seconds. Must be |
| [workers-kv_identifier](workers-kv-identifier.md) | primitive | Identifier. |
| [workers-kv_key](workers-kv-key.md) | object | A name for a value. A value stored under a given k |
| [workers-kv_key_name](workers-kv-key-name.md) | primitive | A key's name. The name may be at most 512 bytes. A |
| [workers-kv_key_name_bulk](workers-kv-key-name-bulk.md) | primitive | A key's name. The name may be at most 512 bytes. A |
| [workers-kv_list_metadata](workers-kv-list-metadata.md) | allOf |  |
| [workers-kv_messages](workers-kv-messages.md) | array |  |
| [workers-kv_metadata](workers-kv-metadata.md) | allOf |  |
| [workers-kv_namespace](workers-kv-namespace.md) | object |  |
| [workers-kv_namespace_identifier](workers-kv-namespace-identifier.md) | primitive | Namespace identifier tag. |
| [workers-kv_namespace_title](workers-kv-namespace-title.md) | primitive | A human-readable string name for a Namespace. |
| [workers-kv_result_info](workers-kv-result-info.md) | object |  |
| [workers-kv_value](workers-kv-value.md) | anyOf | A byte sequence to be stored, up to 25 MiB in leng |
