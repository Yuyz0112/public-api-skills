# Incident Custom Fields

Custom fields allow you to enrich PagerDuty incidents with critical and helpful metadata throughout the incident lifecycle.


## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/incidents/custom_fields` | List Fields | [View](../operations/listCustomFieldsFields.md) |
| POST | `/incidents/custom_fields` | Create a Field | [View](../operations/createCustomFieldsField.md) |
| GET | `/incidents/custom_fields/{field_id}` | Get a Field | [View](../operations/getCustomFieldsField.md) |
| PUT | `/incidents/custom_fields/{field_id}` | Update a Field | [View](../operations/updateCustomFieldsField.md) |
| DELETE | `/incidents/custom_fields/{field_id}` | Delete a Field | [View](../operations/deleteCustomFieldsField.md) |
| GET | `/incidents/custom_fields/{field_id}/field_options` | List Field Options | [View](../operations/listCustomFieldsFieldOptions.md) |
| POST | `/incidents/custom_fields/{field_id}/field_options` | Create a Field Option | [View](../operations/createCustomFieldsFieldOption.md) |
| PUT | `/incidents/custom_fields/{field_id}/field_options/{field_option_id}` | Update a Field Option | [View](../operations/updateCustomFieldsFieldOption.md) |
| DELETE | `/incidents/custom_fields/{field_id}/field_options/{field_option_id}` | Delete a Field Option | [View](../operations/deleteCustomFieldsFieldOption.md) |
