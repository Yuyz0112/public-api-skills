# POST /alert_grouping_settings

**Resource:** [Alert Grouping Settings](../resources/Alert-Grouping-Settings.md)
**Create an Alert Grouping Setting**
**Operation ID:** `postAlertGroupingSettings`

Create a new Alert Grouping Setting.

The settings part of Alert Grouper service allows us to create Alert Grouping Settings and configs that are required to be used during grouping of the alerts.

This endpoint will be used to create an instance of AlertGroupingSettings for either one service or many services that are in the alert group setting.

Scoped OAuth requires: `services.write`


## Request Body

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 201 | The new Alert Grouping Setting. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |

