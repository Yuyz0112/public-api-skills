# GET /custom_fields/{custom_field_gid}

**Resource:** [Custom fields](../resources/Custom-fields.md)
**Get a custom field**
**Operation ID:** `getCustomField`

<b>Required scope: </b><code>custom_fields:read</code>

Get the complete definition of a custom field’s metadata.

Since custom fields can be defined for one of a number of types, and
these types have different data and behaviors, there are fields that are
relevant to a particular type. For instance, as noted above, enum_options
is only relevant for the enum type and defines the set of choices that
the enum could represent. The examples below show some of these
type-specific custom field definitions.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `opt_fields` | query | string[] | No | This endpoint returns a resource which excludes some properties by default. To include those optional properties, set this query parameter to a comma-separated list of the properties you wish to include. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successfully retrieved the complete definition of a custom field’s metadata. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

## Security

- **personalAccessToken**
- **oauth2**: custom_fields:read
