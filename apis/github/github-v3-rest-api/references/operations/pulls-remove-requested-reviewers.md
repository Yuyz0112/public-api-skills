# DELETE /repos/{owner}/{repo}/pulls/{pull_number}/requested_reviewers

**Resource:** [pulls](../resources/pulls.md)
**Remove requested reviewers from a pull request**
**Operation ID:** `pulls/remove-requested-reviewers`

Removes review requests from a pull request for a given set of users and/or teams.

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 422 | (reference) |

**Success Response Schema:**

[pull-request-simple](../schemas/pull-request-simple/pull-request-simple.md)

