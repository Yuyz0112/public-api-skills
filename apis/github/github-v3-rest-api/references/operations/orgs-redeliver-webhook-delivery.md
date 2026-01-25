# POST /orgs/{org}/hooks/{hook_id}/deliveries/{delivery_id}/attempts

**Resource:** [orgs](../resources/orgs.md)
**Redeliver a delivery for an organization webhook**
**Operation ID:** `orgs/redeliver-webhook-delivery`

Redeliver a delivery for a webhook configured in an organization.

You must be an organization owner to use this endpoint.

OAuth app tokens and personal access tokens (classic) need `admin:org_hook` scope. OAuth apps cannot list, view, or edit
webhooks that they did not create and users cannot list, view, or edit webhooks that were created by OAuth apps.

## Responses

| Status | Description |
|--------|-------------|
| 202 | (reference) |
| 400 | (reference) |
| 422 | (reference) |

