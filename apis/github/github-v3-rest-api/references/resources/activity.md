# activity

Activity APIs provide access to notifications, subscriptions, and timelines.

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/events` | List public events | [View](../operations/activity-list-public-events.md) |
| GET | `/feeds` | Get feeds | [View](../operations/activity-get-feeds.md) |
| GET | `/networks/{owner}/{repo}/events` | List public events for a network of repositories | [View](../operations/activity-list-public-events-for-repo-network.md) |
| GET | `/notifications` | List notifications for the authenticated user | [View](../operations/activity-list-notifications-for-authenticated-user.md) |
| PUT | `/notifications` | Mark notifications as read | [View](../operations/activity-mark-notifications-as-read.md) |
| GET | `/notifications/threads/{thread_id}` | Get a thread | [View](../operations/activity-get-thread.md) |
| DELETE | `/notifications/threads/{thread_id}` | Mark a thread as done | [View](../operations/activity-mark-thread-as-done.md) |
| PATCH | `/notifications/threads/{thread_id}` | Mark a thread as read | [View](../operations/activity-mark-thread-as-read.md) |
| GET | `/notifications/threads/{thread_id}/subscription` | Get a thread subscription for the authenticated user | [View](../operations/activity-get-thread-subscription-for-authenticated-user.md) |
| PUT | `/notifications/threads/{thread_id}/subscription` | Set a thread subscription | [View](../operations/activity-set-thread-subscription.md) |
| DELETE | `/notifications/threads/{thread_id}/subscription` | Delete a thread subscription | [View](../operations/activity-delete-thread-subscription.md) |
| GET | `/orgs/{org}/events` | List public organization events | [View](../operations/activity-list-public-org-events.md) |
| GET | `/repos/{owner}/{repo}/events` | List repository events | [View](../operations/activity-list-repo-events.md) |
| GET | `/repos/{owner}/{repo}/notifications` | List repository notifications for the authenticated user | [View](../operations/activity-list-repo-notifications-for-authenticated-user.md) |
| PUT | `/repos/{owner}/{repo}/notifications` | Mark repository notifications as read | [View](../operations/activity-mark-repo-notifications-as-read.md) |
| GET | `/repos/{owner}/{repo}/stargazers` | List stargazers | [View](../operations/activity-list-stargazers-for-repo.md) |
| GET | `/repos/{owner}/{repo}/subscribers` | List watchers | [View](../operations/activity-list-watchers-for-repo.md) |
| GET | `/repos/{owner}/{repo}/subscription` | Get a repository subscription | [View](../operations/activity-get-repo-subscription.md) |
| PUT | `/repos/{owner}/{repo}/subscription` | Set a repository subscription | [View](../operations/activity-set-repo-subscription.md) |
| DELETE | `/repos/{owner}/{repo}/subscription` | Delete a repository subscription | [View](../operations/activity-delete-repo-subscription.md) |
| GET | `/user/starred` | List repositories starred by the authenticated user | [View](../operations/activity-list-repos-starred-by-authenticated-user.md) |
| GET | `/user/starred/{owner}/{repo}` | Check if a repository is starred by the authenticated user | [View](../operations/activity-check-repo-is-starred-by-authenticated-user.md) |
| PUT | `/user/starred/{owner}/{repo}` | Star a repository for the authenticated user | [View](../operations/activity-star-repo-for-authenticated-user.md) |
| DELETE | `/user/starred/{owner}/{repo}` | Unstar a repository for the authenticated user | [View](../operations/activity-unstar-repo-for-authenticated-user.md) |
| GET | `/user/subscriptions` | List repositories watched by the authenticated user | [View](../operations/activity-list-watched-repos-for-authenticated-user.md) |
| GET | `/users/{username}/events` | List events for the authenticated user | [View](../operations/activity-list-events-for-authenticated-user.md) |
| GET | `/users/{username}/events/orgs/{org}` | List organization events for the authenticated user | [View](../operations/activity-list-org-events-for-authenticated-user.md) |
| GET | `/users/{username}/events/public` | List public events for a user | [View](../operations/activity-list-public-events-for-user.md) |
| GET | `/users/{username}/received_events` | List events received by the authenticated user | [View](../operations/activity-list-received-events-for-user.md) |
| GET | `/users/{username}/received_events/public` | List public events received by a user | [View](../operations/activity-list-received-public-events-for-user.md) |
| GET | `/users/{username}/starred` | List repositories starred by a user | [View](../operations/activity-list-repos-starred-by-user.md) |
| GET | `/users/{username}/subscriptions` | List repositories watched by a user | [View](../operations/activity-list-repos-watched-by-user.md) |
