# PUT /api/v4/elasticsearch_indexed_namespaces/rollback

**Resource:** [Advanced search rollout](../resources/Advanced-search-rollout.md)
**Rollback namespaces to be indexed down to n%**
**Operation ID:** `putApiV4ElasticsearchIndexedNamespacesRollback`

This feature was introduced in GitLab 12.7.

**DEPRECATED**: This endpoint is deprecated and for GitLab.com use only.

This will only ever decrease the number of indexed namespaces. Providing a value higher than the current rolled out percentage will have no effect.

This percentage is never persisted but is used to calculate the number of namespaces to rollback.


## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

