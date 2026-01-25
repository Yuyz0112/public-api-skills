# GET /orgs/{org}/hooks/{hook_id}

**Resource:** [orgs](../resources/orgs.md)
**Get an organization webhook**
**Operation ID:** `orgs/get-webhook`

Returns a webhook configured in an organization. To get only the webhook
`config` properties, see "[Get a webhook configuration for an organization](/rest/orgs/webhooks#get-a-webhook-configuration-for-an-organization).

You must be an organization owner to use this endpoint.

OAuth app tokens and personal access tokens (classic) need `admin:org_hook` scope. OAuth apps cannot list, view, or edit
webhooks that they did not create and users cannot list, view, or edit webhooks that were created by OAuth apps.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 404 | (reference) |

**Success Response Schema:**

[org-hook](../schemas/org-hook/org-hook.md)

