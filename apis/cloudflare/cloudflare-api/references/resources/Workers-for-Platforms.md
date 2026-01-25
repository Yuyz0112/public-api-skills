# Workers for Platforms

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/accounts/{account_id}/workers/dispatch/namespaces` | List dispatch namespaces | [View](../operations/namespace-worker-list.md) |
| POST | `/accounts/{account_id}/workers/dispatch/namespaces` | Create dispatch namespace | [View](../operations/namespace-worker-create.md) |
| GET | `/accounts/{account_id}/workers/dispatch/namespaces/{dispatch_namespace}` | Get dispatch namespace | [View](../operations/namespace-worker-get-namespace.md) |
| PUT | `/accounts/{account_id}/workers/dispatch/namespaces/{dispatch_namespace}` | Update dispatch namespace | [View](../operations/namespace-worker-put-namespace.md) |
| DELETE | `/accounts/{account_id}/workers/dispatch/namespaces/{dispatch_namespace}` | Delete dispatch namespace | [View](../operations/namespace-worker-delete-namespace.md) |
| PATCH | `/accounts/{account_id}/workers/dispatch/namespaces/{dispatch_namespace}` | Patch dispatch namespace | [View](../operations/namespace-worker-patch-namespace.md) |
| GET | `/accounts/{account_id}/workers/dispatch/namespaces/{dispatch_namespace}/scripts` | List Scripts in Namespace | [View](../operations/namespace-worker-list-scripts.md) |
| DELETE | `/accounts/{account_id}/workers/dispatch/namespaces/{dispatch_namespace}/scripts` | Delete Scripts in Namespace | [View](../operations/namespace-worker-delete-scripts.md) |
| GET | `/accounts/{account_id}/workers/dispatch/namespaces/{dispatch_namespace}/scripts/{script_name}` | Worker Details | [View](../operations/namespace-worker-script-worker-details.md) |
| PUT | `/accounts/{account_id}/workers/dispatch/namespaces/{dispatch_namespace}/scripts/{script_name}` | Upload Worker Module | [View](../operations/namespace-worker-script-upload-worker-module.md) |
| DELETE | `/accounts/{account_id}/workers/dispatch/namespaces/{dispatch_namespace}/scripts/{script_name}` | Delete Worker | [View](../operations/namespace-worker-script-delete-worker.md) |
| POST | `/accounts/{account_id}/workers/dispatch/namespaces/{dispatch_namespace}/scripts/{script_name}/assets-upload-session` | Create Assets Upload Session | [View](../operations/namespace-worker-script-update-create-assets-upload-session.md) |
| GET | `/accounts/{account_id}/workers/dispatch/namespaces/{dispatch_namespace}/scripts/{script_name}/bindings` | Get Script Bindings | [View](../operations/namespace-worker-get-script-bindings.md) |
| GET | `/accounts/{account_id}/workers/dispatch/namespaces/{dispatch_namespace}/scripts/{script_name}/content` | Get Script Content | [View](../operations/namespace-worker-get-script-content.md) |
| PUT | `/accounts/{account_id}/workers/dispatch/namespaces/{dispatch_namespace}/scripts/{script_name}/content` | Put Script Content | [View](../operations/namespace-worker-put-script-content.md) |
| GET | `/accounts/{account_id}/workers/dispatch/namespaces/{dispatch_namespace}/scripts/{script_name}/secrets` | List Script Secrets | [View](../operations/namespace-worker-list-script-secrets.md) |
| PUT | `/accounts/{account_id}/workers/dispatch/namespaces/{dispatch_namespace}/scripts/{script_name}/secrets` | Add script secret | [View](../operations/namespace-worker-put-script-secrets.md) |
| GET | `/accounts/{account_id}/workers/dispatch/namespaces/{dispatch_namespace}/scripts/{script_name}/secrets/{secret_name}` | Get secret binding | [View](../operations/namespace-worker-get-script-secrets.md) |
| DELETE | `/accounts/{account_id}/workers/dispatch/namespaces/{dispatch_namespace}/scripts/{script_name}/secrets/{secret_name}` | Delete script secret | [View](../operations/namespace-worker-delete-script-secret.md) |
| GET | `/accounts/{account_id}/workers/dispatch/namespaces/{dispatch_namespace}/scripts/{script_name}/settings` | Get Script Settings | [View](../operations/namespace-worker-get-script-settings.md) |
| PATCH | `/accounts/{account_id}/workers/dispatch/namespaces/{dispatch_namespace}/scripts/{script_name}/settings` | Patch Script Settings | [View](../operations/namespace-worker-patch-script-settings.md) |
| GET | `/accounts/{account_id}/workers/dispatch/namespaces/{dispatch_namespace}/scripts/{script_name}/tags` | Get Script Tags | [View](../operations/namespace-worker-get-script-tags.md) |
| PUT | `/accounts/{account_id}/workers/dispatch/namespaces/{dispatch_namespace}/scripts/{script_name}/tags` | Put Script Tags | [View](../operations/namespace-worker-put-script-tags.md) |
| PUT | `/accounts/{account_id}/workers/dispatch/namespaces/{dispatch_namespace}/scripts/{script_name}/tags/{tag}` | Put Script Tag | [View](../operations/namespace-worker-put-script-tag.md) |
| DELETE | `/accounts/{account_id}/workers/dispatch/namespaces/{dispatch_namespace}/scripts/{script_name}/tags/{tag}` | Delete Script Tag | [View](../operations/namespace-worker-delete-script-tag.md) |
