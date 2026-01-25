# GET /attachments/{attachment_gid}

**Resource:** [Attachments](../resources/Attachments.md)
**Get an attachment**
**Operation ID:** `getAttachment`

<b>Required scope: </b><code>attachments:read</code>

Get the full record for a single attachment.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `opt_fields` | query | string[] | No | This endpoint returns a resource which excludes some properties by default. To include those optional properties, set this query parameter to a comma-separated list of the properties you wish to include. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successfully retrieved the record for a single attachment. |
| 400 | (reference) |
| 401 | (reference) |
| 402 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 424 | (reference) |
| 500 | (reference) |
| 501 | (reference) |
| 503 | (reference) |
| 504 | (reference) |

## Security

- **personalAccessToken**
- **oauth2**: attachments:read
