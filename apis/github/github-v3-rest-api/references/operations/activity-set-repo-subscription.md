# PUT /repos/{owner}/{repo}/subscription

**Resource:** [activity](../resources/activity.md)
**Set a repository subscription**
**Operation ID:** `activity/set-repo-subscription`

If you would like to watch a repository, set `subscribed` to `true`. If you would like to ignore notifications made within a repository, set `ignored` to `true`. If you would like to stop watching a repository, [delete the repository's subscription](https://docs.github.com/rest/activity/watching#delete-a-repository-subscription) completely.

## Request Body

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |

**Success Response Schema:**

[repository-subscription](../schemas/repository-subscription/repository-subscription.md)

