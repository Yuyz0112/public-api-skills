# PUT /incidents/types/{type_id_or_name}/custom_fields/{field_id}

**Resource:** [Incident Types](../resources/Incident-Types.md)
**Update a Custom Field for an Incident Type**
**Operation ID:** `updateIncidentTypeCustomField`

Update a custom field for an incident type. Field Options can also be updated within the same call.

Custom Fields (CF) are a feature which will allow customers to extend Incidents with their own custom data,
to provide additional context and support features such as customized filtering, search and analytics.
Custom Fields can be applied to different incident types.

Scoped OAuth requires: `custom_fields.write`


## Request Body

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | The updated custom field object. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

