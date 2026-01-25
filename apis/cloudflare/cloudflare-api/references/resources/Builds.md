# Builds

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/accounts/{account_id}/builds/builds` | Get builds by version IDs | [View](../operations/getBuildsByVersionIds.md) |
| GET | `/accounts/{account_id}/builds/builds/latest` | Get latest builds by script IDs | [View](../operations/getLatestBuildsByScripts.md) |
| GET | `/accounts/{account_id}/builds/builds/{build_uuid}` | Get build by UUID | [View](../operations/getBuildByUuid.md) |
| PUT | `/accounts/{account_id}/builds/builds/{build_uuid}/cancel` | Cancel build | [View](../operations/cancelBuildByUuid.md) |
| GET | `/accounts/{account_id}/builds/builds/{build_uuid}/logs` | Get build logs | [View](../operations/getBuildLogs.md) |
