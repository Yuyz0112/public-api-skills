# PUT /alert_grouping_settings/{id}

**Resource:** [Alert Grouping Settings](../resources/Alert-Grouping-Settings.md)
**Update an Alert Grouping Setting**
**Operation ID:** `putAlertGroupingSetting`

Update an Alert Grouping Setting.

The settings part of Alert Grouper service allows us to create Alert Grouping Settings and configs that are required to be used during grouping of the alerts.

if `services` are not provided in the request, then the existing services will not be removed from the setting.

Scoped OAuth requires: `services.write`


## Request Body

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | The updated Alert Grouping Setting. |
| 400 | (reference) |
| 401 | (reference) |
| 404 | (reference) |

