# GET /orgs/{org}/hooks

**Resource:** [orgs](../resources/orgs.md)
**List organization webhooks**
**Operation ID:** `orgs/list-webhooks`

List webhooks for an organization.

The authenticated user must be an organization owner to use this endpoint.

OAuth app tokens and personal access tokens (classic) need `admin:org_hook` scope. OAuth apps cannot list, view, or edit
webhooks that they did not create and users cannot list, view, or edit webhooks that were created by OAuth apps.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 404 | (reference) |

**Success Response Schema:**

Array of [org-hook](../schemas/org-hook/org-hook.md)

