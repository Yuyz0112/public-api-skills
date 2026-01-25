# PUT /enum_options/{enum_option_gid}

**Resource:** [Custom fields](../resources/Custom-fields.md)
**Update an enum option**
**Operation ID:** `updateEnumOption`

<b>Required scope: </b><code>custom_fields:write</code>

Updates an existing enum option. Enum custom fields require at least one enabled enum option.
Locked custom fields can only be updated by the user who locked the field.
Returns the full record of the updated enum option.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `opt_fields` | query | string[] | No | This endpoint returns a resource which excludes some properties by default. To include those optional properties, set this query parameter to a comma-separated list of the properties you wish to include. |

## Request Body

The enum option object to update

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successfully updated the specified custom field enum. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

## Security

- **personalAccessToken**
- **oauth2**: custom_fields:write
