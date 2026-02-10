# Imports

Operations related to imports.

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| POST | `/api/v4/import/github/gists` | Import User Gists | [View](../operations/postApiV4ImportGithubGists.md) |
| GET | `/api/v4/bulk_imports` | List all GitLab Migrations | [View](../operations/getApiV4BulkImports.md) |
| POST | `/api/v4/bulk_imports` | Start a new GitLab Migration | [View](../operations/postApiV4BulkImports.md) |
| GET | `/api/v4/bulk_imports/entities` | List all GitLab Migrations' entities | [View](../operations/getApiV4BulkImportsEntities.md) |
| GET | `/api/v4/bulk_imports/{import_id}` | Get GitLab Migration details | [View](../operations/getApiV4BulkImportsImportId.md) |
| GET | `/api/v4/bulk_imports/{import_id}/entities` | List GitLab Migration entities | [View](../operations/getApiV4BulkImportsImportIdEntities.md) |
| GET | `/api/v4/bulk_imports/{import_id}/entities/{entity_id}` | Get GitLab Migration entity details | [View](../operations/getApiV4BulkImportsImportIdEntitiesEntityId.md) |
| GET | `/api/v4/bulk_imports/{import_id}/entities/{entity_id}/failures` | Get GitLab Migration entity failures | [View](../operations/getApiV4BulkImportsImportIdEntitiesEntityIdFailures.md) |
| POST | `/api/v4/bulk_imports/{import_id}/cancel` | Cancel GitLab Migration | [View](../operations/postApiV4BulkImportsImportIdCancel.md) |
