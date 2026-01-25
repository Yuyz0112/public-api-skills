# GET /orgs/{org}/hooks/{hook_id}/deliveries

**Resource:** [orgs](../resources/orgs.md)
**List deliveries for an organization webhook**
**Operation ID:** `orgs/list-webhook-deliveries`

Returns a list of webhook deliveries for a webhook configured in an organization.

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

Array of [hook-delivery-item](../schemas/hook-delivery-item/hook-delivery-item.md)

