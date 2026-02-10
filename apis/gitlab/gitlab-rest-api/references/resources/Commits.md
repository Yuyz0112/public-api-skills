# Commits

Operations related to commits.

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/api/v4/projects/{id}/repository/commits` | Get a project repository commits | [View](../operations/getApiV4ProjectsIdRepositoryCommits.md) |
| POST | `/api/v4/projects/{id}/repository/commits` | Create a new commit | [View](../operations/postApiV4ProjectsIdRepositoryCommits.md) |
| POST | `/api/v4/projects/{id}/repository/commits/authorize` | Authorize commits upload | [View](../operations/postApiV4ProjectsIdRepositoryCommitsAuthorize.md) |
| GET | `/api/v4/projects/{id}/repository/commits/{sha}` | Get a specific commit of a project | [View](../operations/getApiV4ProjectsIdRepositoryCommitsSha.md) |
| GET | `/api/v4/projects/{id}/repository/commits/{sha}/diff` | Get the diff for a specific commit of a project | [View](../operations/getApiV4ProjectsIdRepositoryCommitsShaDiff.md) |
| GET | `/api/v4/projects/{id}/repository/commits/{sha}/comments` | Get a commit's comments | [View](../operations/getApiV4ProjectsIdRepositoryCommitsShaComments.md) |
| POST | `/api/v4/projects/{id}/repository/commits/{sha}/comments` | Post comment to commit | [View](../operations/postApiV4ProjectsIdRepositoryCommitsShaComments.md) |
| GET | `/api/v4/projects/{id}/repository/commits/{sha}/sequence` | Get the sequence count of a commit SHA | [View](../operations/getApiV4ProjectsIdRepositoryCommitsShaSequence.md) |
| POST | `/api/v4/projects/{id}/repository/commits/{sha}/cherry_pick` | Cherry pick commit into a branch | [View](../operations/postApiV4ProjectsIdRepositoryCommitsShaCherryPick.md) |
| POST | `/api/v4/projects/{id}/repository/commits/{sha}/revert` | Revert a commit in a branch | [View](../operations/postApiV4ProjectsIdRepositoryCommitsShaRevert.md) |
| GET | `/api/v4/projects/{id}/repository/commits/{sha}/refs` | Get all references a commit is pushed to | [View](../operations/getApiV4ProjectsIdRepositoryCommitsShaRefs.md) |
| GET | `/api/v4/projects/{id}/repository/commits/{sha}/merge_requests` | Get Merge Requests associated with a commit | [View](../operations/getApiV4ProjectsIdRepositoryCommitsShaMergeRequests.md) |
| GET | `/api/v4/projects/{id}/repository/commits/{sha}/signature` | Get a commit's signature | [View](../operations/getApiV4ProjectsIdRepositoryCommitsShaSignature.md) |
