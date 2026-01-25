# Status Pages

Status Pages can be public or private read-only pages, that display the status of some predefined set of services, to be shared with customers or internal stakeholders.


## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/status_pages` | List Status Pages | [View](../operations/listStatusPages.md) |
| GET | `/status_pages/{id}/impacts` | List Status Page Impacts | [View](../operations/listStatusPageImpacts.md) |
| GET | `/status_pages/{id}/impacts/{impact_id}` | Get a Status Page Impact | [View](../operations/getStatusPageImpact.md) |
| GET | `/status_pages/{id}/services` | List Status Page Services | [View](../operations/listStatusPageServices.md) |
| GET | `/status_pages/{id}/services/{service_id}` | Get a Status Page Service | [View](../operations/getStatusPageService.md) |
| GET | `/status_pages/{id}/severities` | List Status Page Severities | [View](../operations/listStatusPageSeverities.md) |
| GET | `/status_pages/{id}/severities/{severity_id}` | Get a Status Page Severity | [View](../operations/getStatusPageSeverity.md) |
| GET | `/status_pages/{id}/statuses` | List Status Page Statuses | [View](../operations/listStatusPageStatuses.md) |
| GET | `/status_pages/{id}/statuses/{status_id}` | Get a Status Page Status | [View](../operations/getStatusPageStatus.md) |
| GET | `/status_pages/{id}/posts` | List Status Page Posts | [View](../operations/listStatusPagePosts.md) |
| POST | `/status_pages/{id}/posts` | Create a Status Page Post | [View](../operations/createStatusPagePost.md) |
| GET | `/status_pages/{id}/posts/{post_id}` | Get a Status Page Post | [View](../operations/getStatusPagePost.md) |
| PUT | `/status_pages/{id}/posts/{post_id}` | Update a Status Page Post | [View](../operations/updateStatusPagePost.md) |
| DELETE | `/status_pages/{id}/posts/{post_id}` | Delete a Status Page Post | [View](../operations/deleteStatusPagePost.md) |
| GET | `/status_pages/{id}/posts/{post_id}/post_updates` | List Status Page Post Updates | [View](../operations/listStatusPagePostUpdates.md) |
| POST | `/status_pages/{id}/posts/{post_id}/post_updates` | Create a Status Page Post Update | [View](../operations/createStatusPagePostUpdate.md) |
| GET | `/status_pages/{id}/posts/{post_id}/post_updates/{post_update_id}` | Get a Status Page Post Update | [View](../operations/getPostUpdate.md) |
| PUT | `/status_pages/{id}/posts/{post_id}/post_updates/{post_update_id}` | Update a Status Page Post Update | [View](../operations/updateStatusPagePostUpdate.md) |
| DELETE | `/status_pages/{id}/posts/{post_id}/post_updates/{post_update_id}` | Delete a Status Page Post Update | [View](../operations/deleteStatusPagePostUpdate.md) |
| GET | `/status_pages/{id}/posts/{post_id}/postmortem` | Get a Post Postmortem | [View](../operations/getPostmortem.md) |
| PUT | `/status_pages/{id}/posts/{post_id}/postmortem` | Update a Post Postmortem | [View](../operations/updateStatusPagePostmortem.md) |
| POST | `/status_pages/{id}/posts/{post_id}/postmortem` | Create a Post Postmortem | [View](../operations/createStatusPagePostmortem.md) |
| DELETE | `/status_pages/{id}/posts/{post_id}/postmortem` | Delete a Post Postmortem | [View](../operations/deleteStatusPagePostmortem.md) |
| GET | `/status_pages/{id}/subscriptions` | List Status Page Subscriptions | [View](../operations/listStatusPageSubscriptions.md) |
| POST | `/status_pages/{id}/subscriptions` | Create a Status Page Subscription | [View](../operations/createStatusPageSubscription.md) |
| GET | `/status_pages/{id}/subscriptions/{subscription_id}` | Get a Status Page Subscription | [View](../operations/getStatusPageSubscription.md) |
| DELETE | `/status_pages/{id}/subscriptions/{subscription_id}` | Delete a Status Page Subscription | [View](../operations/deleteStatusPageSubscription.md) |
