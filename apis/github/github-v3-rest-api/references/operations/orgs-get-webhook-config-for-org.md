# GET /orgs/{org}/hooks/{hook_id}/config

**Resource:** [orgs](../resources/orgs.md)
**Get a webhook configuration for an organization**
**Operation ID:** `orgs/get-webhook-config-for-org`

Returns the webhook configuration for an organization. To get more information about the webhook, including the `active` state and `events`, use "[Get an organization webhook ](/rest/orgs/webhooks#get-an-organization-webhook)."

You must be an organization owner to use this endpoint.

OAuth app tokens and personal access tokens (classic) need `admin:org_hook` scope. OAuth apps cannot list, view, or edit
webhooks that they did not create and users cannot list, view, or edit webhooks that were created by OAuth apps.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |

**Success Response Schema:**

[webhook-config](../schemas/webhook-config/webhook-config.md)

