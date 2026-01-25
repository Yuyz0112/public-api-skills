# Incident Types

Incident Types are a feature which will allow customers to categorize incidents, such as a security incident, a major incident, or a fraud incident.


## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/incidents/types` | List incident types | [View](../operations/listIncidentTypes.md) |
| POST | `/incidents/types` | Create an Incident Type | [View](../operations/createIncidentType.md) |
| GET | `/incidents/types/{type_id_or_name}` | Get an Incident Type | [View](../operations/getIncidentType.md) |
| PUT | `/incidents/types/{type_id_or_name}` | Update an Incident Type | [View](../operations/updateIncidentType.md) |
| GET | `/incidents/types/{type_id_or_name}/custom_fields` | List Incident Type Custom Fields | [View](../operations/listIncidentTypeCustomFields.md) |
| POST | `/incidents/types/{type_id_or_name}/custom_fields` | Create a Custom Field for an Incident Type | [View](../operations/createIncidentTypeCustomField.md) |
| GET | `/incidents/types/{type_id_or_name}/custom_fields/{field_id}` | Get an Incident Type Custom Field | [View](../operations/getIncidentTypeCustomField.md) |
| PUT | `/incidents/types/{type_id_or_name}/custom_fields/{field_id}` | Update a Custom Field for an Incident Type | [View](../operations/updateIncidentTypeCustomField.md) |
| DELETE | `/incidents/types/{type_id_or_name}/custom_fields/{field_id}` | Delete a Custom Field for an Incident Type | [View](../operations/deleteIncidentTypeCustomField.md) |
| GET | `/incidents/types/{type_id_or_name}/custom_fields/{field_id}/field_options` | List Field Options on a Custom Field | [View](../operations/listIncidentTypeCustomField.md) |
| POST | `/incidents/types/{type_id_or_name}/custom_fields/{field_id}/field_options` | Create a Field Option for a Custom Field | [View](../operations/createIncidentTypeCustomFieldFieldOptions.md) |
| GET | `/incidents/types/{type_id_or_name}/custom_fields/{field_id}/field_options/{field_option_id}` | Get a Field Option on a Custom Field | [View](../operations/getIncidentTypeCustomFieldFieldOptions.md) |
| PUT | `/incidents/types/{type_id_or_name}/custom_fields/{field_id}/field_options/{field_option_id}` | Update a Field Option for a Custom Field | [View](../operations/updateIncidentTypeCustomFieldFieldOption.md) |
| DELETE | `/incidents/types/{type_id_or_name}/custom_fields/{field_id}/field_options/{field_option_id}` | Delete a Field Option for a Custom Field | [View](../operations/deleteIncidentTypeCustomFieldFieldOption.md) |
