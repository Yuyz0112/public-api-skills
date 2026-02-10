# POST /api/v4/projects/{id}/issues/{issue_iid}/metric_images

**Resource:** [Metric images](../resources/Metric-images.md)
**Upload a metric image for an issue**
**Operation ID:** `postApiV4ProjectsIdIssuesIssueIidMetricImages`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |

## Request Body

**Required:** Yes

**Content Types:** `multipart/form-data`

## Responses

| Status | Description |
|--------|-------------|
| 201 | Created |

**Success Response Schema:**

[APIEntitiesIssuableMetricImage](../schemas/APIEntitiesIssuableMetricImage/APIEntitiesIssuableMetricImage.md)

