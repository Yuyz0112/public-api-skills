# DELETE /custom_fields/{custom_field_gid}

**Resource:** [Custom fields](../resources/Custom-fields.md)
**Delete a custom field**
**Operation ID:** `deleteCustomField`

A specific, existing custom field can be deleted by making a DELETE request on the URL for that custom field.
Locked custom fields can only be deleted by the user who locked the field.
Returns an empty data record.

## Responses

| Status | Description |
|--------|-------------|
| 200 | The custom field was successfully deleted. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

## Security

- **personalAccessToken**
- **oauth2**
