# GET /orgs/{org}/hooks/{hook_id}/deliveries/{delivery_id}

**Resource:** [orgs](../resources/orgs.md)
**Get a webhook delivery for an organization webhook**
**Operation ID:** `orgs/get-webhook-delivery`

Returns a delivery for a webhook configured in an organization.

You must be an organization owner to use this endpoint.

OAuth app tokens and personal access tokens (classic) need `admin:org_hook` scope. OAuth apps cannot list, view, or edit
webhooks that they did not create and users cannot list, view, or edit webhooks that were created by OAuth apps.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 400 | (reference) |
| 422 | (reference) |

**Success Response Schema:**

[hook-delivery](../schemas/hook-delivery/hook-delivery.md)

