# GET /api/v4/projects/{id}/issues/{issue_iid}/metric_images

**Resource:** [Metric images](../resources/Metric-images.md)
**Metric Images for issue**
**Operation ID:** `getApiV4ProjectsIdIssuesIssueIidMetricImages`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

**Success Response Schema:**

[APIEntitiesIssuableMetricImage](../schemas/APIEntitiesIssuableMetricImage/APIEntitiesIssuableMetricImage.md)

