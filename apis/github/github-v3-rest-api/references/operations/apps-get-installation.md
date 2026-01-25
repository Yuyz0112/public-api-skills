# GET /app/installations/{installation_id}

**Resource:** [apps](../resources/apps.md)
**Get an installation for the authenticated app**
**Operation ID:** `apps/get-installation`

Enables an authenticated GitHub App to find an installation's information using the installation id.

You must use a [JWT](https://docs.github.com/apps/building-github-apps/authenticating-with-github-apps/#authenticating-as-a-github-app) to access this endpoint.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 404 | (reference) |

**Success Response Schema:**

[installation](../schemas/installation/installation.md)

