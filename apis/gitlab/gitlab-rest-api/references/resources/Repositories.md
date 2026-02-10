# Repositories

Operations related to repositories.

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/api/v4/projects/{id}/repository/tree` | Get a project repository tree | [View](../operations/getApiV4ProjectsIdRepositoryTree.md) |
| GET | `/api/v4/projects/{id}/repository/blobs/{sha}/raw` | Get raw blob contents from the repository | [View](../operations/getApiV4ProjectsIdRepositoryBlobsShaRaw.md) |
| GET | `/api/v4/projects/{id}/repository/blobs/{sha}` | Get a blob from the repository | [View](../operations/getApiV4ProjectsIdRepositoryBlobsSha.md) |
| GET | `/api/v4/projects/{id}/repository/archive` | Get an archive of the repository | [View](../operations/getApiV4ProjectsIdRepositoryArchive.md) |
| GET | `/api/v4/projects/{id}/repository/compare` | Compare two branches, tags, or commits | [View](../operations/getApiV4ProjectsIdRepositoryCompare.md) |
| GET | `/api/v4/projects/{id}/repository/health` | Get repository health | [View](../operations/getApiV4ProjectsIdRepositoryHealth.md) |
| GET | `/api/v4/projects/{id}/repository/contributors` | Get repository contributors | [View](../operations/getApiV4ProjectsIdRepositoryContributors.md) |
| GET | `/api/v4/projects/{id}/repository/merge_base` | Get the common ancestor between commits | [View](../operations/getApiV4ProjectsIdRepositoryMergeBase.md) |
| GET | `/api/v4/projects/{id}/repository/changelog` | Generates a changelog section for a release and returns it | [View](../operations/getApiV4ProjectsIdRepositoryChangelog.md) |
| POST | `/api/v4/projects/{id}/repository/changelog` | Generates a changelog section for a release and commits it in a changelog file | [View](../operations/postApiV4ProjectsIdRepositoryChangelog.md) |
