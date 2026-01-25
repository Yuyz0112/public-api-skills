# GET /app/installations

**Resource:** [apps](../resources/apps.md)
**List installations for the authenticated app**
**Operation ID:** `apps/list-installations`

The permissions the installation has are included under the `permissions` key.

You must use a [JWT](https://docs.github.com/apps/building-github-apps/authenticating-with-github-apps/#authenticating-as-a-github-app) to access this endpoint.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `outdated` | query | string | No |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | The permissions the installation has are included under the `permissions` key. |

**Success Response Schema:**

Array of [installation](../schemas/installation/installation.md)

