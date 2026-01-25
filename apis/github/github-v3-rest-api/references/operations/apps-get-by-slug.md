# GET /apps/{app_slug}

**Resource:** [apps](../resources/apps.md)
**Get an app**
**Operation ID:** `apps/get-by-slug`

> [!NOTE]
> The `:app_slug` is just the URL-friendly name of your GitHub App. You can find this on the settings page for your GitHub App (e.g., `https://github.com/settings/apps/:app_slug`).

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 403 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

[integration](../schemas/integration/integration.md)

