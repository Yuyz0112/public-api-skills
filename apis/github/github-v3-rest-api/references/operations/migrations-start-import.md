# PUT /repos/{owner}/{repo}/import

**Resource:** [migrations](../resources/migrations.md)
**Start an import**
**Operation ID:** `migrations/start-import`
⚠️ **Deprecated**

Start a source import to a GitHub repository using GitHub Importer.
Importing into a GitHub repository with GitHub Actions enabled is not supported and will
return a status `422 Unprocessable Entity` response.

> [!WARNING]
> **Endpoint closing down notice:** Due to very low levels of usage and available alternatives, this endpoint is closing down and will no longer be available from 00:00 UTC on April 12, 2024. For more details and alternatives, see the [changelog](https://gh.io/source-imports-api-deprecation).

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 201 | Response |
| 404 | (reference) |
| 422 | (reference) |
| 503 | (reference) |

**Success Response Schema:**

[import](../schemas/import/import.md)

