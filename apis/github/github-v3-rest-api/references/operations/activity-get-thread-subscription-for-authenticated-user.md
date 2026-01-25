# GET /notifications/threads/{thread_id}/subscription

**Resource:** [activity](../resources/activity.md)
**Get a thread subscription for the authenticated user**
**Operation ID:** `activity/get-thread-subscription-for-authenticated-user`

This checks to see if the current user is subscribed to a thread. You can also [get a repository subscription](https://docs.github.com/rest/activity/watching#get-a-repository-subscription).

Note that subscriptions are only generated if a user is participating in a conversation--for example, they've replied to the thread, were **@mentioned**, or manually subscribe to a thread.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 304 | (reference) |
| 401 | (reference) |
| 403 | (reference) |

**Success Response Schema:**

[thread-subscription](../schemas/thread-subscription/thread-subscription.md)

