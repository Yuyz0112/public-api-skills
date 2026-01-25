# Secrets Store

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/accounts/{account_id}/secrets_store/quota` | View secret usage | [View](../operations/secrets-store-quota.md) |
| GET | `/accounts/{account_id}/secrets_store/stores` | List account stores | [View](../operations/secrets-store-list.md) |
| POST | `/accounts/{account_id}/secrets_store/stores` | Create a store | [View](../operations/secrets-store-create.md) |
| DELETE | `/accounts/{account_id}/secrets_store/stores/{store_id}` | Delete a store | [View](../operations/secrets-store-delete-by-id.md) |
| GET | `/accounts/{account_id}/secrets_store/stores/{store_id}/secrets` | List store secrets | [View](../operations/secrets-store-secrets-list.md) |
| POST | `/accounts/{account_id}/secrets_store/stores/{store_id}/secrets` | Create a secret | [View](../operations/secrets-store-secret-create.md) |
| DELETE | `/accounts/{account_id}/secrets_store/stores/{store_id}/secrets` | Delete secrets | [View](../operations/secrets-store-delete-bulk.md) |
| GET | `/accounts/{account_id}/secrets_store/stores/{store_id}/secrets/{secret_id}` | Get a secret by ID | [View](../operations/secrets-store-get-by-id.md) |
| DELETE | `/accounts/{account_id}/secrets_store/stores/{store_id}/secrets/{secret_id}` | Delete a secret | [View](../operations/secrets-store-secret-delete-by-id.md) |
| PATCH | `/accounts/{account_id}/secrets_store/stores/{store_id}/secrets/{secret_id}` | Patch a secret | [View](../operations/secrets-store-patch-by-id.md) |
| POST | `/accounts/{account_id}/secrets_store/stores/{store_id}/secrets/{secret_id}/duplicate` | Duplicate Secret | [View](../operations/secrets-store-duplicate-by-id.md) |
