# AlertGroupingParameters

Defines how alerts on this service will be automatically grouped into incidents. Note that the alert grouping features are available only on certain plans. To turn grouping off set the type to null.
This attribute has been deprecated and configuration via [Alert Grouping Settings](https://developer.pagerduty.com/api-reference/587edbc8ff416-create-an-alert-grouping-setting) resource is encouraged.


**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `type` | enum: time, intelligent, content_based... | No |  |
| `config` | any | No |  |

