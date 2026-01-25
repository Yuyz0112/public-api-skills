# PUT /webhooks/{webhook_gid}

**Resource:** [Webhooks](../resources/Webhooks.md)
**Update a webhook**
**Operation ID:** `updateWebhook`

<b>Required scope: </b><code>webhooks:write</code>

An existing webhook's filters can be updated by making a PUT request on the URL for that webhook. Note that the webhook's previous `filters` array will be completely overwritten by the `filters` sent in the PUT request.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `opt_fields` | query | string[] | No | This endpoint returns a resource which excludes some properties by default. To include those optional properties, set this query parameter to a comma-separated list of the properties you wish to include. |

## Request Body

The updated filters for the webhook.

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successfully updated the webhook. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

## Security

- **personalAccessToken**
- **oauth2**: webhooks:write
