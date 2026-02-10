# POST /api/v4/projects/{id}/alert_management_alerts/{alert_iid}/metric_images

**Resource:** [Alert management](../resources/Alert-management.md)
**Upload a metric image for an alert**
**Operation ID:** `postApiV4ProjectsIdAlertManagementAlertsAlertIidMetricImages`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |
| `alert_iid` | path | integer | Yes | The IID of the Alert |

## Request Body

**Required:** Yes

**Content Types:** `multipart/form-data`

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 403 | Forbidden |

**Success Response Schema:**

[APIEntitiesMetricImage](../schemas/APIEntitiesMetricImage/APIEntitiesMetricImage.md)

