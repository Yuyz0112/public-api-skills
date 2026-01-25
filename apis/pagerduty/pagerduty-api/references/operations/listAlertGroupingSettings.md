# GET /alert_grouping_settings

**Resource:** [Alert Grouping Settings](../resources/Alert-Grouping-Settings.md)
**List alert grouping settings**
**Operation ID:** `listAlertGroupingSettings`

List all of your alert grouping settings including both single service settings and global content based settings.

The settings part of Alert Grouper service allows us to create Alert Grouping Settings and configs that are required to be used during grouping of the alerts.

Scoped OAuth requires: `services.read`


## Responses

| Status | Description |
|--------|-------------|
| 200 | An array of alert grouping settings. |
| 401 | (reference) |

