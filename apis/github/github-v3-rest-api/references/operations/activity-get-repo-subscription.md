# GET /repos/{owner}/{repo}/subscription

**Resource:** [activity](../resources/activity.md)
**Get a repository subscription**
**Operation ID:** `activity/get-repo-subscription`

Gets information about whether the authenticated user is subscribed to the repository.

## Responses

| Status | Description |
|--------|-------------|
| 200 | if you subscribe to the repository |
| 403 | (reference) |
| 404 | Not Found if you don't subscribe to the repository |

**Success Response Schema:**

[repository-subscription](../schemas/repository-subscription/repository-subscription.md)

