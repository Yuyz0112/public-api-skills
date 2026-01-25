# PUT /rates/{rate_gid}

**Resource:** [Rates](../resources/Rates.md)
**Update a rate**
**Operation ID:** `updateRate`

An existing rate can be updated by making a PUT request on the URL for
that rate. Only the fields provided in the `data` block will be updated;
any unspecified fields will remain unchanged. (note that at this time, the only field that can be updated is the `rate` field.)

Returns the complete updated rate record.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `opt_fields` | query | string[] | No | This endpoint returns a resource which excludes some properties by default. To include those optional properties, set this query parameter to a comma-separated list of the properties you wish to include. |

## Request Body

The updated fields for the rate.

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successfully updated the rate. |
| 400 | (reference) |
| 401 | (reference) |
| 402 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

## Security

- **personalAccessToken**
- **oauth2**
