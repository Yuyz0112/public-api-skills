# PATCH /orgs/{org}/hooks/{hook_id}/config

**Resource:** [orgs](../resources/orgs.md)
**Update a webhook configuration for an organization**
**Operation ID:** `orgs/update-webhook-config-for-org`

Updates the webhook configuration for an organization. To update more information about the webhook, including the `active` state and `events`, use "[Update an organization webhook ](/rest/orgs/webhooks#update-an-organization-webhook)."

You must be an organization owner to use this endpoint.

OAuth app tokens and personal access tokens (classic) need `admin:org_hook` scope. OAuth apps cannot list, view, or edit
webhooks that they did not create and users cannot list, view, or edit webhooks that were created by OAuth apps.

## Request Body

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |

**Success Response Schema:**

[webhook-config](../schemas/webhook-config/webhook-config.md)

