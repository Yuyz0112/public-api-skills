# PATCH /orgs/{org}/hooks/{hook_id}

**Resource:** [orgs](../resources/orgs.md)
**Update an organization webhook**
**Operation ID:** `orgs/update-webhook`

Updates a webhook configured in an organization. When you update a webhook,
the `secret` will be overwritten. If you previously had a `secret` set, you must
provide the same `secret` or set a new `secret` or the secret will be removed. If
you are only updating individual webhook `config` properties, use "[Update a webhook
configuration for an organization](/rest/orgs/webhooks#update-a-webhook-configuration-for-an-organization)".

You must be an organization owner to use this endpoint.

OAuth app tokens and personal access tokens (classic) need `admin:org_hook` scope. OAuth apps cannot list, view, or edit
webhooks that they did not create and users cannot list, view, or edit webhooks that were created by OAuth apps.

## Request Body

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 404 | (reference) |
| 422 | (reference) |

**Success Response Schema:**

[org-hook](../schemas/org-hook/org-hook.md)

