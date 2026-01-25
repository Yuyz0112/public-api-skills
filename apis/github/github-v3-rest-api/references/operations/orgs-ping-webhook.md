# POST /orgs/{org}/hooks/{hook_id}/pings

**Resource:** [orgs](../resources/orgs.md)
**Ping an organization webhook**
**Operation ID:** `orgs/ping-webhook`

This will trigger a [ping event](https://docs.github.com/webhooks/#ping-event)
to be sent to the hook.

You must be an organization owner to use this endpoint.

OAuth app tokens and personal access tokens (classic) need `admin:org_hook` scope. OAuth apps cannot list, view, or edit
webhooks that they did not create and users cannot list, view, or edit webhooks that were created by OAuth apps.

## Responses

| Status | Description |
|--------|-------------|
| 204 | Response |
| 404 | (reference) |

