# GET /repos/{owner}/{repo}/pulls/{pull_number}/requested_reviewers

**Resource:** [pulls](../resources/pulls.md)
**Get all requested reviewers for a pull request**
**Operation ID:** `pulls/list-requested-reviewers`

Gets the users or teams whose review is requested for a pull request. Once a requested reviewer submits a review, they are no longer considered a requested reviewer. Their review will instead be returned by the [List reviews for a pull request](https://docs.github.com/rest/pulls/reviews#list-reviews-for-a-pull-request) operation.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |

**Success Response Schema:**

[pull-request-review-request](../schemas/pull-request-review-request/pull-request-review-request.md)

