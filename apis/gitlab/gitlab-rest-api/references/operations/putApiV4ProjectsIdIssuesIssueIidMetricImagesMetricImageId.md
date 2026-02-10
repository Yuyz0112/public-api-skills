# PUT /api/v4/projects/{id}/issues/{issue_iid}/metric_images/{metric_image_id}

**Resource:** [Metric images](../resources/Metric-images.md)
**Update a metric image for an issue**
**Operation ID:** `putApiV4ProjectsIdIssuesIssueIidMetricImagesMetricImageId`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |
| `metric_image_id` | path | integer | Yes | The ID of metric image |

## Request Body

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

**Success Response Schema:**

[APIEntitiesIssuableMetricImage](../schemas/APIEntitiesIssuableMetricImage/APIEntitiesIssuableMetricImage.md)

