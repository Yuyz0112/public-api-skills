# PUT /custom_fields/{custom_field_gid}

**Resource:** [Custom fields](../resources/Custom-fields.md)
**Update a custom field**
**Operation ID:** `updateCustomField`

<b>Required scope: </b><code>custom_fields:write</code>

A specific, existing custom field can be updated by making a PUT request on the URL for that custom field. Only the fields provided in the `data` block will be updated; any unspecified fields will remain unchanged
When using this method, it is best to specify only those fields you wish to change, or else you may overwrite changes made by another user since you last retrieved the custom field.
A custom field’s `type` cannot be updated.
An enum custom field’s `enum_options` cannot be updated with this endpoint. Instead see “Work With Enum Options” for information on how to update `enum_options`.
Locked custom fields can only be updated by the user who locked the field.
Returns the complete updated custom field record.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `opt_fields` | query | string[] | No | This endpoint returns a resource which excludes some properties by default. To include those optional properties, set this query parameter to a comma-separated list of the properties you wish to include. |

## Request Body

The custom field object with all updated properties.

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | The custom field was successfully updated. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

## Security

- **personalAccessToken**
- **oauth2**: custom_fields:write
