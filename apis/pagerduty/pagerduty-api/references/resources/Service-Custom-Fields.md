# Service Custom Fields

Custom fields allow you to enrich PagerDuty services with critical and helpful metadata throughout the Service lifecycle.


## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/services/custom_fields` | List Fields | [View](../operations/listServiceCustomFields.md) |
| POST | `/services/custom_fields` | Create a Field | [View](../operations/createServiceCustomField.md) |
| GET | `/services/custom_fields/{field_id}` | Get a Field | [View](../operations/getServiceCustomField.md) |
| PUT | `/services/custom_fields/{field_id}` | Update a Field | [View](../operations/updateServiceCustomField.md) |
| DELETE | `/services/custom_fields/{field_id}` | Delete a Field | [View](../operations/deleteServiceCustomField.md) |
| GET | `/services/custom_fields/{field_id}/field_options` | List Field Options | [View](../operations/listServiceCustomFieldOptions.md) |
| POST | `/services/custom_fields/{field_id}/field_options` | Create a Field Option | [View](../operations/createServiceCustomFieldOption.md) |
| GET | `/services/custom_fields/{field_id}/field_options/{field_option_id}` | Get a Field Option | [View](../operations/getServiceCustomFieldOption.md) |
| PUT | `/services/custom_fields/{field_id}/field_options/{field_option_id}` | Update a Field Option | [View](../operations/updateServiceCustomFieldOption.md) |
| DELETE | `/services/custom_fields/{field_id}/field_options/{field_option_id}` | Delete a Field Option | [View](../operations/deleteServiceCustomFieldOption.md) |
