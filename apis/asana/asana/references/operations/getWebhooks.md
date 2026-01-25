# GET /webhooks

**Resource:** [Webhooks](../resources/Webhooks.md)
**Get multiple webhooks**
**Operation ID:** `getWebhooks`

<b>Required scope: </b><code>webhooks:read</code>

Get the compact representation of all webhooks your app has registered for the authenticated user in the given workspace.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `workspace` | query | string | Yes | The workspace to query for webhooks in. |
| `resource` | query | string | No | Only return webhooks for the given resource. |
| `opt_fields` | query | string[] | No | This endpoint returns a resource which excludes some properties by default. To include those optional properties, set this query parameter to a comma-separated list of the properties you wish to include. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successfully retrieved the requested webhooks. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

## Security

- **personalAccessToken**
- **oauth2**: webhooks:read
