# POST /repos/{owner}/{repo}/releases

**Resource:** [repos](../resources/repos.md)
**Create a release**
**Operation ID:** `repos/create-release`

Users with push access to the repository can create a release.

This endpoint triggers [notifications](https://docs.github.com/github/managing-subscriptions-and-notifications-on-github/about-notifications). Creating content too quickly using this endpoint may result in secondary rate limiting. For more information, see "[Rate limits for the API](https://docs.github.com/rest/using-the-rest-api/rate-limits-for-the-rest-api#about-secondary-rate-limits)" and "[Best practices for using the REST API](https://docs.github.com/rest/guides/best-practices-for-using-the-rest-api)."

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 201 | Response |
| 404 | Not Found if the discussion category name is invalid |
| 422 | (reference) |

**Success Response Schema:**

[release](../schemas/release/release.md)

