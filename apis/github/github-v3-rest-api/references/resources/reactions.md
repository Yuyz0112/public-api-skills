# reactions

Interact with reactions to various GitHub entities.

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/repos/{owner}/{repo}/comments/{comment_id}/reactions` | List reactions for a commit comment | [View](../operations/reactions-list-for-commit-comment.md) |
| POST | `/repos/{owner}/{repo}/comments/{comment_id}/reactions` | Create reaction for a commit comment | [View](../operations/reactions-create-for-commit-comment.md) |
| DELETE | `/repos/{owner}/{repo}/comments/{comment_id}/reactions/{reaction_id}` | Delete a commit comment reaction | [View](../operations/reactions-delete-for-commit-comment.md) |
| GET | `/repos/{owner}/{repo}/issues/comments/{comment_id}/reactions` | List reactions for an issue comment | [View](../operations/reactions-list-for-issue-comment.md) |
| POST | `/repos/{owner}/{repo}/issues/comments/{comment_id}/reactions` | Create reaction for an issue comment | [View](../operations/reactions-create-for-issue-comment.md) |
| DELETE | `/repos/{owner}/{repo}/issues/comments/{comment_id}/reactions/{reaction_id}` | Delete an issue comment reaction | [View](../operations/reactions-delete-for-issue-comment.md) |
| GET | `/repos/{owner}/{repo}/issues/{issue_number}/reactions` | List reactions for an issue | [View](../operations/reactions-list-for-issue.md) |
| POST | `/repos/{owner}/{repo}/issues/{issue_number}/reactions` | Create reaction for an issue | [View](../operations/reactions-create-for-issue.md) |
| DELETE | `/repos/{owner}/{repo}/issues/{issue_number}/reactions/{reaction_id}` | Delete an issue reaction | [View](../operations/reactions-delete-for-issue.md) |
| GET | `/repos/{owner}/{repo}/pulls/comments/{comment_id}/reactions` | List reactions for a pull request review comment | [View](../operations/reactions-list-for-pull-request-review-comment.md) |
| POST | `/repos/{owner}/{repo}/pulls/comments/{comment_id}/reactions` | Create reaction for a pull request review comment | [View](../operations/reactions-create-for-pull-request-review-comment.md) |
| DELETE | `/repos/{owner}/{repo}/pulls/comments/{comment_id}/reactions/{reaction_id}` | Delete a pull request comment reaction | [View](../operations/reactions-delete-for-pull-request-comment.md) |
| GET | `/repos/{owner}/{repo}/releases/{release_id}/reactions` | List reactions for a release | [View](../operations/reactions-list-for-release.md) |
| POST | `/repos/{owner}/{repo}/releases/{release_id}/reactions` | Create reaction for a release | [View](../operations/reactions-create-for-release.md) |
| DELETE | `/repos/{owner}/{repo}/releases/{release_id}/reactions/{reaction_id}` | Delete a release reaction | [View](../operations/reactions-delete-for-release.md) |
