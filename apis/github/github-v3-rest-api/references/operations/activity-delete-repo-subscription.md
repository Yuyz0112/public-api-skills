# DELETE /repos/{owner}/{repo}/subscription

**Resource:** [activity](../resources/activity.md)
**Delete a repository subscription**
**Operation ID:** `activity/delete-repo-subscription`

This endpoint should only be used to stop watching a repository. To control whether or not you wish to receive notifications from a repository, [set the repository's subscription manually](https://docs.github.com/rest/activity/watching#set-a-repository-subscription).

## Responses

| Status | Description |
|--------|-------------|
| 204 | Response |

