# POST /custom_fields/{custom_field_gid}/enum_options/insert

**Resource:** [Custom fields](../resources/Custom-fields.md)
**Reorder a custom field's enum**
**Operation ID:** `insertEnumOptionForCustomField`

<b>Required scope: </b><code>custom_fields:write</code>

Moves a particular enum option to be either before or after another specified enum option in the custom field.
Locked custom fields can only be reordered by the user who locked the field.

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
| 200 | Custom field enum option successfully reordered. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

## Security

- **personalAccessToken**
- **oauth2**: custom_fields:write
