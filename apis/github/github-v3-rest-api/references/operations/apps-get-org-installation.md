# GET /orgs/{org}/installation

**Resource:** [apps](../resources/apps.md)
**Get an organization installation for the authenticated app**
**Operation ID:** `apps/get-org-installation`

Enables an authenticated GitHub App to find the organization's installation information.

You must use a [JWT](https://docs.github.com/apps/building-github-apps/authenticating-with-github-apps/#authenticating-as-a-github-app) to access this endpoint.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |

**Success Response Schema:**

[installation](../schemas/installation/installation.md)

