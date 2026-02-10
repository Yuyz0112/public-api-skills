# POST /api/v4/projects/{id}/alert_management_alerts/{alert_iid}/metric_images/authorize

**Resource:** [Alert management](../resources/Alert-management.md)
**Workhorse authorize metric image file upload**
**Operation ID:** `postApiV4ProjectsIdAlertManagementAlertsAlertIidMetricImagesAuthorize`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |
| `alert_iid` | path | integer | Yes | The IID of the Alert |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 403 | Forbidden |

