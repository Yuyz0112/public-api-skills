# pulls

Interact with GitHub Pull Requests.

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/repos/{owner}/{repo}/pulls` | List pull requests | [View](../operations/pulls-list.md) |
| POST | `/repos/{owner}/{repo}/pulls` | Create a pull request | [View](../operations/pulls-create.md) |
| GET | `/repos/{owner}/{repo}/pulls/comments` | List review comments in a repository | [View](../operations/pulls-list-review-comments-for-repo.md) |
| GET | `/repos/{owner}/{repo}/pulls/comments/{comment_id}` | Get a review comment for a pull request | [View](../operations/pulls-get-review-comment.md) |
| DELETE | `/repos/{owner}/{repo}/pulls/comments/{comment_id}` | Delete a review comment for a pull request | [View](../operations/pulls-delete-review-comment.md) |
| PATCH | `/repos/{owner}/{repo}/pulls/comments/{comment_id}` | Update a review comment for a pull request | [View](../operations/pulls-update-review-comment.md) |
| GET | `/repos/{owner}/{repo}/pulls/{pull_number}` | Get a pull request | [View](../operations/pulls-get.md) |
| PATCH | `/repos/{owner}/{repo}/pulls/{pull_number}` | Update a pull request | [View](../operations/pulls-update.md) |
| GET | `/repos/{owner}/{repo}/pulls/{pull_number}/comments` | List review comments on a pull request | [View](../operations/pulls-list-review-comments.md) |
| POST | `/repos/{owner}/{repo}/pulls/{pull_number}/comments` | Create a review comment for a pull request | [View](../operations/pulls-create-review-comment.md) |
| POST | `/repos/{owner}/{repo}/pulls/{pull_number}/comments/{comment_id}/replies` | Create a reply for a review comment | [View](../operations/pulls-create-reply-for-review-comment.md) |
| GET | `/repos/{owner}/{repo}/pulls/{pull_number}/commits` | List commits on a pull request | [View](../operations/pulls-list-commits.md) |
| GET | `/repos/{owner}/{repo}/pulls/{pull_number}/files` | List pull requests files | [View](../operations/pulls-list-files.md) |
| GET | `/repos/{owner}/{repo}/pulls/{pull_number}/merge` | Check if a pull request has been merged | [View](../operations/pulls-check-if-merged.md) |
| PUT | `/repos/{owner}/{repo}/pulls/{pull_number}/merge` | Merge a pull request | [View](../operations/pulls-merge.md) |
| GET | `/repos/{owner}/{repo}/pulls/{pull_number}/requested_reviewers` | Get all requested reviewers for a pull request | [View](../operations/pulls-list-requested-reviewers.md) |
| POST | `/repos/{owner}/{repo}/pulls/{pull_number}/requested_reviewers` | Request reviewers for a pull request | [View](../operations/pulls-request-reviewers.md) |
| DELETE | `/repos/{owner}/{repo}/pulls/{pull_number}/requested_reviewers` | Remove requested reviewers from a pull request | [View](../operations/pulls-remove-requested-reviewers.md) |
| GET | `/repos/{owner}/{repo}/pulls/{pull_number}/reviews` | List reviews for a pull request | [View](../operations/pulls-list-reviews.md) |
| POST | `/repos/{owner}/{repo}/pulls/{pull_number}/reviews` | Create a review for a pull request | [View](../operations/pulls-create-review.md) |
| GET | `/repos/{owner}/{repo}/pulls/{pull_number}/reviews/{review_id}` | Get a review for a pull request | [View](../operations/pulls-get-review.md) |
| PUT | `/repos/{owner}/{repo}/pulls/{pull_number}/reviews/{review_id}` | Update a review for a pull request | [View](../operations/pulls-update-review.md) |
| DELETE | `/repos/{owner}/{repo}/pulls/{pull_number}/reviews/{review_id}` | Delete a pending review for a pull request | [View](../operations/pulls-delete-pending-review.md) |
| GET | `/repos/{owner}/{repo}/pulls/{pull_number}/reviews/{review_id}/comments` | List comments for a pull request review | [View](../operations/pulls-list-comments-for-review.md) |
| PUT | `/repos/{owner}/{repo}/pulls/{pull_number}/reviews/{review_id}/dismissals` | Dismiss a review for a pull request | [View](../operations/pulls-dismiss-review.md) |
| POST | `/repos/{owner}/{repo}/pulls/{pull_number}/reviews/{review_id}/events` | Submit a review for a pull request | [View](../operations/pulls-submit-review.md) |
| PUT | `/repos/{owner}/{repo}/pulls/{pull_number}/update-branch` | Update a pull request branch | [View](../operations/pulls-update-branch.md) |
