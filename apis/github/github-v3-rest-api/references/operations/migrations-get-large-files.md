# GET /repos/{owner}/{repo}/import/large_files

**Resource:** [migrations](../resources/migrations.md)
**Get large files**
**Operation ID:** `migrations/get-large-files`
⚠️ **Deprecated**

List files larger than 100MB found during the import

> [!WARNING]
> **Endpoint closing down notice:** Due to very low levels of usage and available alternatives, this endpoint is closing down and will no longer be available from 00:00 UTC on April 12, 2024. For more details and alternatives, see the [changelog](https://gh.io/source-imports-api-deprecation).

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 503 | (reference) |

**Success Response Schema:**

Array of [porter-large-file](../schemas/porter-large-file/porter-large-file.md)

