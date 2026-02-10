# DELETE /api/v4/projects/{id}/alert_management_alerts/{alert_iid}/metric_images/{metric_image_id}

**Resource:** [Alert management](../resources/Alert-management.md)
**Remove a metric image for an alert**
**Operation ID:** `deleteApiV4ProjectsIdAlertManagementAlertsAlertIidMetricImagesMetricImageId`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |
| `alert_iid` | path | integer | Yes | The IID of the Alert |
| `metric_image_id` | path | integer | Yes | The ID of metric image |

## Responses

| Status | Description |
|--------|-------------|
| 204 | No Content |
| 403 | Forbidden |
| 422 | Unprocessable entity |

