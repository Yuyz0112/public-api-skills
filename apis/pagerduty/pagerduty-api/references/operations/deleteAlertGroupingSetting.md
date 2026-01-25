# DELETE /alert_grouping_settings/{id}

**Resource:** [Alert Grouping Settings](../resources/Alert-Grouping-Settings.md)
**Delete an Alert Grouping Setting**
**Operation ID:** `deleteAlertGroupingSetting`

Delete an existing Alert Grouping Setting.

The settings part of Alert Grouper service allows us to create Alert Grouping Settings and configs that are required to be used during grouping of the alerts.

Scoped OAuth requires: `services.write`


## Responses

| Status | Description |
|--------|-------------|
| 204 | The Alert Grouping Setting was deleted successfully. |
| 401 | (reference) |
| 404 | (reference) |

