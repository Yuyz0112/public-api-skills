# Issue bulk operations

This resource represents the issue bulk operations. Use it to move multiple issues from one project to another project or edit fields of multiple issues in one go.  


For additional clarity, we have created a page with further examples and answers to frequently asked questions related to these APIs. You can access it here: [Bulk operation APIs: additional examples and FAQ](https://developer.atlassian.com/cloud/jira/platform/bulk-operation-additional-examples-and-faqs/).

### Authentication ###

Access to the issue bulk operations requires authentication. For information on how to authenticate API requests, refer to the [Basic auth for REST APIs documentation](https://developer.atlassian.com/cloud/jira/platform/basic-auth-for-rest-apis/).

### Rate limiting ###

The bulk edit and move APIs are subject to the usual rate limiting infrastructure in Jira. For more information, refer to [Rate limiting](https://developer.atlassian.com/cloud/jira/platform/rate-limiting/). Additionally, at any given time, only 5 concurrent requests can be sent across all users.

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| POST | `/rest/api/3/bulk/issues/delete` | Bulk delete issues | [View](../operations/submitBulkDelete.md) |
| GET | `/rest/api/3/bulk/issues/fields` | Get bulk editable fields | [View](../operations/getBulkEditableFields.md) |
| POST | `/rest/api/3/bulk/issues/fields` | Bulk edit issues | [View](../operations/submitBulkEdit.md) |
| POST | `/rest/api/3/bulk/issues/move` | Bulk move issues | [View](../operations/submitBulkMove.md) |
| GET | `/rest/api/3/bulk/issues/transition` | Get available transitions | [View](../operations/getAvailableTransitions.md) |
| POST | `/rest/api/3/bulk/issues/transition` | Bulk transition issue statuses | [View](../operations/submitBulkTransition.md) |
| POST | `/rest/api/3/bulk/issues/unwatch` | Bulk unwatch issues | [View](../operations/submitBulkUnwatch.md) |
| POST | `/rest/api/3/bulk/issues/watch` | Bulk watch issues | [View](../operations/submitBulkWatch.md) |
| GET | `/rest/api/3/bulk/queue/{taskId}` | Get bulk issue operation progress | [View](../operations/getBulkOperationProgress.md) |
