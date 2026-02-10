# DELETE /api/v4/projects/{id}/issues/{issue_iid}/metric_images/{metric_image_id}

**Resource:** [Metric images](../resources/Metric-images.md)
**Remove a metric image for an issue**
**Operation ID:** `deleteApiV4ProjectsIdIssuesIssueIidMetricImagesMetricImageId`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |
| `metric_image_id` | path | integer | Yes | The ID of metric image |

## Responses

| Status | Description |
|--------|-------------|
| 204 | No Content |

