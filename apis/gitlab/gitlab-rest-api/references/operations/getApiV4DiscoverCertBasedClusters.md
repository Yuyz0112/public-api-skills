# GET /api/v4/discover-cert-based-clusters

**Resource:** [Clusters](../resources/Clusters.md)
**Discover all descendant certificate-based clusters in a group**
**Operation ID:** `getApiV4DiscoverCertBasedClusters`

This feature was introduced in GitLab 17.9. It will be removed in 18.0.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `group_id` | query | integer | Yes | The group ID to find all certificate-based clusters in the hierarchy |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 403 | Forbidden |

**Success Response Schema:**

[APIEntitiesDiscoveredClusters](../schemas/APIEntitiesDiscoveredClusters/APIEntitiesDiscoveredClusters.md)

