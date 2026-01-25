# PUT /repos/{owner}/{repo}/pulls/{pull_number}/merge

**Resource:** [pulls](../resources/pulls.md)
**Merge a pull request**
**Operation ID:** `pulls/merge`

Merges a pull request into the base branch.
This endpoint triggers [notifications](https://docs.github.com/github/managing-subscriptions-and-notifications-on-github/about-notifications). Creating content too quickly using this endpoint may result in secondary rate limiting. For more information, see "[Rate limits for the API](https://docs.github.com/rest/using-the-rest-api/rate-limits-for-the-rest-api#about-secondary-rate-limits)" and "[Best practices for using the REST API](https://docs.github.com/rest/guides/best-practices-for-using-the-rest-api)."

## Request Body

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | if merge was successful |
| 403 | (reference) |
| 404 | (reference) |
| 405 | Method Not Allowed if merge cannot be performed |
| 409 | Conflict if sha was provided and pull request head did not match |
| 422 | (reference) |

**Success Response Schema:**

[pull-request-merge-result](../schemas/pull-request-merge-result/pull-request-merge-result.md)

