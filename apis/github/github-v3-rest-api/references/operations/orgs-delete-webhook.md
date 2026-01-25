# DELETE /orgs/{org}/hooks/{hook_id}

**Resource:** [orgs](../resources/orgs.md)
**Delete an organization webhook**
**Operation ID:** `orgs/delete-webhook`

Delete a webhook for an organization.

The authenticated user must be an organization owner to use this endpoint.

OAuth app tokens and personal access tokens (classic) need `admin:org_hook` scope. OAuth apps cannot list, view, or edit
webhooks that they did not create and users cannot list, view, or edit webhooks that were created by OAuth apps.

## Responses

| Status | Description |
|--------|-------------|
| 204 | Response |
| 404 | (reference) |

