# git

Raw Git functionality.

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| POST | `/repos/{owner}/{repo}/git/blobs` | Create a blob | [View](../operations/git-create-blob.md) |
| GET | `/repos/{owner}/{repo}/git/blobs/{file_sha}` | Get a blob | [View](../operations/git-get-blob.md) |
| POST | `/repos/{owner}/{repo}/git/commits` | Create a commit | [View](../operations/git-create-commit.md) |
| GET | `/repos/{owner}/{repo}/git/commits/{commit_sha}` | Get a commit object | [View](../operations/git-get-commit.md) |
| GET | `/repos/{owner}/{repo}/git/matching-refs/{ref}` | List matching references | [View](../operations/git-list-matching-refs.md) |
| GET | `/repos/{owner}/{repo}/git/ref/{ref}` | Get a reference | [View](../operations/git-get-ref.md) |
| POST | `/repos/{owner}/{repo}/git/refs` | Create a reference | [View](../operations/git-create-ref.md) |
| DELETE | `/repos/{owner}/{repo}/git/refs/{ref}` | Delete a reference | [View](../operations/git-delete-ref.md) |
| PATCH | `/repos/{owner}/{repo}/git/refs/{ref}` | Update a reference | [View](../operations/git-update-ref.md) |
| POST | `/repos/{owner}/{repo}/git/tags` | Create a tag object | [View](../operations/git-create-tag.md) |
| GET | `/repos/{owner}/{repo}/git/tags/{tag_sha}` | Get a tag | [View](../operations/git-get-tag.md) |
| POST | `/repos/{owner}/{repo}/git/trees` | Create a tree | [View](../operations/git-create-tree.md) |
| GET | `/repos/{owner}/{repo}/git/trees/{tree_sha}` | Get a tree | [View](../operations/git-get-tree.md) |
