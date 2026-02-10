# GET /api/v4/projects/{id}/alert_management_alerts/{alert_iid}/metric_images

**Resource:** [Alert management](../resources/Alert-management.md)
**Metric Images for alert**
**Operation ID:** `getApiV4ProjectsIdAlertManagementAlertsAlertIidMetricImages`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |
| `alert_iid` | path | integer | Yes | The IID of the Alert |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 404 | Not found |

**Success Response Schema:**

[APIEntitiesMetricImage](../schemas/APIEntitiesMetricImage/APIEntitiesMetricImage.md)

