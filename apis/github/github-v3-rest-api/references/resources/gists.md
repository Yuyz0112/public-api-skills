# gists

View, modify your gists.

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/gists` | List gists for the authenticated user | [View](../operations/gists-list.md) |
| POST | `/gists` | Create a gist | [View](../operations/gists-create.md) |
| GET | `/gists/public` | List public gists | [View](../operations/gists-list-public.md) |
| GET | `/gists/starred` | List starred gists | [View](../operations/gists-list-starred.md) |
| GET | `/gists/{gist_id}` | Get a gist | [View](../operations/gists-get.md) |
| DELETE | `/gists/{gist_id}` | Delete a gist | [View](../operations/gists-delete.md) |
| PATCH | `/gists/{gist_id}` | Update a gist | [View](../operations/gists-update.md) |
| GET | `/gists/{gist_id}/comments` | List gist comments | [View](../operations/gists-list-comments.md) |
| POST | `/gists/{gist_id}/comments` | Create a gist comment | [View](../operations/gists-create-comment.md) |
| GET | `/gists/{gist_id}/comments/{comment_id}` | Get a gist comment | [View](../operations/gists-get-comment.md) |
| DELETE | `/gists/{gist_id}/comments/{comment_id}` | Delete a gist comment | [View](../operations/gists-delete-comment.md) |
| PATCH | `/gists/{gist_id}/comments/{comment_id}` | Update a gist comment | [View](../operations/gists-update-comment.md) |
| GET | `/gists/{gist_id}/commits` | List gist commits | [View](../operations/gists-list-commits.md) |
| GET | `/gists/{gist_id}/forks` | List gist forks | [View](../operations/gists-list-forks.md) |
| POST | `/gists/{gist_id}/forks` | Fork a gist | [View](../operations/gists-fork.md) |
| GET | `/gists/{gist_id}/star` | Check if a gist is starred | [View](../operations/gists-check-is-starred.md) |
| PUT | `/gists/{gist_id}/star` | Star a gist | [View](../operations/gists-star.md) |
| DELETE | `/gists/{gist_id}/star` | Unstar a gist | [View](../operations/gists-unstar.md) |
| GET | `/gists/{gist_id}/{sha}` | Get a gist revision | [View](../operations/gists-get-revision.md) |
| GET | `/users/{username}/gists` | List gists for a user | [View](../operations/gists-list-for-user.md) |
