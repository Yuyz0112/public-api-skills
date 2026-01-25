# POST /custom_fields/{custom_field_gid}/enum_options

**Resource:** [Custom fields](../resources/Custom-fields.md)
**Create an enum option**
**Operation ID:** `createEnumOptionForCustomField`

<b>Required scope: </b><code>custom_fields:write</code>

Creates an enum option and adds it to this custom field’s list of enum options. A custom field can have at most 500 enum options (including disabled options). By default new enum options are inserted at the end of a custom field’s list.
Locked custom fields can only have enum options added by the user who locked the field.
Returns the full record of the newly created enum option.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `opt_fields` | query | string[] | No | This endpoint returns a resource which excludes some properties by default. To include those optional properties, set this query parameter to a comma-separated list of the properties you wish to include. |

## Request Body

The enum option object to create.

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 201 | Custom field enum option successfully created. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

## Security

- **personalAccessToken**
- **oauth2**: custom_fields:write
