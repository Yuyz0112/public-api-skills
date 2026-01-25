# Workers KV Namespace

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/accounts/{account_id}/storage/kv/namespaces` | List Namespaces | [View](../operations/workers-kv-namespace-list-namespaces.md) |
| POST | `/accounts/{account_id}/storage/kv/namespaces` | Create a Namespace | [View](../operations/workers-kv-namespace-create-a-namespace.md) |
| GET | `/accounts/{account_id}/storage/kv/namespaces/{namespace_id}` | Get a Namespace | [View](../operations/workers-kv-namespace-get-a-namespace.md) |
| PUT | `/accounts/{account_id}/storage/kv/namespaces/{namespace_id}` | Rename a Namespace | [View](../operations/workers-kv-namespace-rename-a-namespace.md) |
| DELETE | `/accounts/{account_id}/storage/kv/namespaces/{namespace_id}` | Remove a Namespace | [View](../operations/workers-kv-namespace-remove-a-namespace.md) |
| PUT | `/accounts/{account_id}/storage/kv/namespaces/{namespace_id}/bulk` | Write multiple key-value pairs | [View](../operations/workers-kv-namespace-write-multiple-key-value-pairs.md) |
| DELETE | `/accounts/{account_id}/storage/kv/namespaces/{namespace_id}/bulk` | Delete multiple key-value pairs | [View](../operations/workers-kv-namespace-delete-multiple-key-value-pairs-deprecated.md) |
| POST | `/accounts/{account_id}/storage/kv/namespaces/{namespace_id}/bulk/delete` | Delete multiple key-value pairs | [View](../operations/workers-kv-namespace-delete-multiple-key-value-pairs.md) |
| POST | `/accounts/{account_id}/storage/kv/namespaces/{namespace_id}/bulk/get` | Get multiple key-value pairs | [View](../operations/workers-kv-namespace-get-multiple-key-value-pairs.md) |
| GET | `/accounts/{account_id}/storage/kv/namespaces/{namespace_id}/keys` | List a Namespace's Keys | [View](../operations/workers-kv-namespace-list-a-namespace-s-keys.md) |
| GET | `/accounts/{account_id}/storage/kv/namespaces/{namespace_id}/metadata/{key_name}` | Read the metadata for a key | [View](../operations/workers-kv-namespace-read-the-metadata-for-a-key.md) |
| GET | `/accounts/{account_id}/storage/kv/namespaces/{namespace_id}/values/{key_name}` | Read key-value pair | [View](../operations/workers-kv-namespace-read-key-value-pair.md) |
| PUT | `/accounts/{account_id}/storage/kv/namespaces/{namespace_id}/values/{key_name}` | Write key-value pair with optional metadata | [View](../operations/workers-kv-namespace-write-key-value-pair-with-metadata.md) |
| DELETE | `/accounts/{account_id}/storage/kv/namespaces/{namespace_id}/values/{key_name}` | Delete key-value pair | [View](../operations/workers-kv-namespace-delete-key-value-pair.md) |
