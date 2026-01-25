# POST /repos/{owner}/{repo}/pulls/{pull_number}/requested_reviewers

**Resource:** [pulls](../resources/pulls.md)
**Request reviewers for a pull request**
**Operation ID:** `pulls/request-reviewers`

Requests reviews for a pull request from a given set of users and/or teams.
This endpoint triggers [notifications](https://docs.github.com/github/managing-subscriptions-and-notifications-on-github/about-notifications). Creating content too quickly using this endpoint may result in secondary rate limiting. For more information, see "[Rate limits for the API](https://docs.github.com/rest/using-the-rest-api/rate-limits-for-the-rest-api#about-secondary-rate-limits)" and "[Best practices for using the REST API](https://docs.github.com/rest/guides/best-practices-for-using-the-rest-api)."

## Request Body

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 201 | Response |
| 403 | (reference) |
| 422 | Unprocessable Entity if user is not a collaborator |

**Success Response Schema:**

[pull-request-simple](../schemas/pull-request-simple/pull-request-simple.md)

