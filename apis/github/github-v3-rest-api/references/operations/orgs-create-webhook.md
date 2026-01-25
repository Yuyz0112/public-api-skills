# POST /orgs/{org}/hooks

**Resource:** [orgs](../resources/orgs.md)
**Create an organization webhook**
**Operation ID:** `orgs/create-webhook`

Create a hook that posts payloads in JSON format.

You must be an organization owner to use this endpoint.

OAuth app tokens and personal access tokens (classic) need `admin:org_hook` scope. OAuth apps cannot list, view, or
edit webhooks that they did not create and users cannot list, view, or edit webhooks that were created by OAuth apps.

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 201 | Response |
| 404 | (reference) |
| 422 | (reference) |

**Success Response Schema:**

[org-hook](../schemas/org-hook/org-hook.md)

