# Worker Script

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| POST | `/accounts/{account_id}/workers/assets/upload` | Upload Assets | [View](../operations/worker-assets-upload.md) |
| GET | `/accounts/{account_id}/workers/scripts` | List Workers | [View](../operations/worker-script-list-workers.md) |
| GET | `/accounts/{account_id}/workers/scripts-search` | Search Workers | [View](../operations/worker-script-search-workers.md) |
| GET | `/accounts/{account_id}/workers/scripts/{script_name}` | Download Worker | [View](../operations/worker-script-download-worker.md) |
| PUT | `/accounts/{account_id}/workers/scripts/{script_name}` | Upload Worker Module | [View](../operations/worker-script-upload-worker-module.md) |
| DELETE | `/accounts/{account_id}/workers/scripts/{script_name}` | Delete Worker | [View](../operations/worker-script-delete-worker.md) |
| POST | `/accounts/{account_id}/workers/scripts/{script_name}/assets-upload-session` | Create Assets Upload Session | [View](../operations/worker-script-update-create-assets-upload-session.md) |
| PUT | `/accounts/{account_id}/workers/scripts/{script_name}/content` | Put script content | [View](../operations/worker-script-put-content.md) |
| GET | `/accounts/{account_id}/workers/scripts/{script_name}/content/v2` | Get script content | [View](../operations/worker-script-get-content.md) |
| GET | `/accounts/{account_id}/workers/scripts/{script_name}/script-settings` | Get Script Settings | [View](../operations/worker-script-settings-get-settings.md) |
| PATCH | `/accounts/{account_id}/workers/scripts/{script_name}/script-settings` | Patch Script Settings | [View](../operations/worker-script-settings-patch-settings.md) |
| GET | `/accounts/{account_id}/workers/scripts/{script_name}/secrets` | List script secrets | [View](../operations/worker-list-script-secrets.md) |
| PUT | `/accounts/{account_id}/workers/scripts/{script_name}/secrets` | Add script secret | [View](../operations/worker-put-script-secret.md) |
| GET | `/accounts/{account_id}/workers/scripts/{script_name}/secrets/{secret_name}` | Get secret binding | [View](../operations/worker-get-script-secret.md) |
| DELETE | `/accounts/{account_id}/workers/scripts/{script_name}/secrets/{secret_name}` | Delete script secret | [View](../operations/worker-delete-script-secret.md) |
| GET | `/accounts/{account_id}/workers/scripts/{script_name}/settings` | Get Settings | [View](../operations/worker-script-get-settings.md) |
| PATCH | `/accounts/{account_id}/workers/scripts/{script_name}/settings` | Patch Settings | [View](../operations/worker-script-patch-settings.md) |
| GET | `/accounts/{account_id}/workers/scripts/{script_name}/subdomain` | Get Worker subdomain | [View](../operations/worker-script-get-subdomain.md) |
| POST | `/accounts/{account_id}/workers/scripts/{script_name}/subdomain` | Post Worker subdomain | [View](../operations/worker-script-post-subdomain.md) |
| DELETE | `/accounts/{account_id}/workers/scripts/{script_name}/subdomain` | Delete Worker subdomain | [View](../operations/worker-script-delete-subdomain.md) |
| GET | `/accounts/{account_id}/workers/scripts/{script_name}/usage-model` | Fetch Usage Model | [View](../operations/worker-script-fetch-usage-model.md) |
| PUT | `/accounts/{account_id}/workers/scripts/{script_name}/usage-model` | Update Usage Model | [View](../operations/worker-script-update-usage-model.md) |
