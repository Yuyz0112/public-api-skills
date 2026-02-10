# Project import

Operations related to project import.

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| POST | `/api/v4/projects/import/authorize` | Workhorse authorize the project import upload | [View](../operations/postApiV4ProjectsImportAuthorize.md) |
| POST | `/api/v4/projects/import` | Create a new project import | [View](../operations/postApiV4ProjectsImport.md) |
| GET | `/api/v4/projects/{id}/import` | Get a project import status | [View](../operations/getApiV4ProjectsIdImport.md) |
| POST | `/api/v4/projects/remote-import` | Create a new project import using a remote object storage path | [View](../operations/postApiV4ProjectsRemoteImport.md) |
| POST | `/api/v4/projects/import-relation/authorize` | Workhorse authorize the project relation import upload | [View](../operations/postApiV4ProjectsImportRelationAuthorize.md) |
| POST | `/api/v4/projects/import-relation` | Re-import a relation into a project | [View](../operations/postApiV4ProjectsImportRelation.md) |
| GET | `/api/v4/projects/{id}/relation-imports` | Get the statuses of relation imports for specified project | [View](../operations/getApiV4ProjectsIdRelationImports.md) |
| POST | `/api/v4/projects/remote-import-s3` | Create a new project import using a file from AWS S3 | [View](../operations/postApiV4ProjectsRemoteImportS3.md) |
| GET | `/api/v4/projects/{id}/export` | Get export status | [View](../operations/getApiV4ProjectsIdExport.md) |
| POST | `/api/v4/projects/{id}/export` | Start export | [View](../operations/postApiV4ProjectsIdExport.md) |
| GET | `/api/v4/projects/{id}/export/download` | Download export | [View](../operations/getApiV4ProjectsIdExportDownload.md) |
| POST | `/api/v4/projects/{id}/export_relations` | Start relations export | [View](../operations/postApiV4ProjectsIdExportRelations.md) |
| GET | `/api/v4/projects/{id}/export_relations/download` | Download relations export | [View](../operations/getApiV4ProjectsIdExportRelationsDownload.md) |
| GET | `/api/v4/projects/{id}/export_relations/status` | Relations export status | [View](../operations/getApiV4ProjectsIdExportRelationsStatus.md) |
| POST | `/api/v4/import/github` | Import a GitHub project | [View](../operations/postApiV4ImportGithub.md) |
| POST | `/api/v4/import/github/cancel` | Cancel GitHub project import | [View](../operations/postApiV4ImportGithubCancel.md) |
| POST | `/api/v4/import/bitbucket_server` | Import a BitBucket Server repository | [View](../operations/postApiV4ImportBitbucketServer.md) |
| POST | `/api/v4/import/bitbucket` | Import a BitBucket Cloud repository | [View](../operations/postApiV4ImportBitbucket.md) |
