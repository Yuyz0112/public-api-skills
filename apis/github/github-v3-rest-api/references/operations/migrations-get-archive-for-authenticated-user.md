# GET /user/migrations/{migration_id}/archive

**Resource:** [migrations](../resources/migrations.md)
**Download a user migration archive**
**Operation ID:** `migrations/get-archive-for-authenticated-user`

Fetches the URL to download the migration archive as a `tar.gz` file. Depending on the resources your repository uses, the migration archive can contain JSON files with data for these objects:

*   attachments
*   bases
*   commit\_comments
*   issue\_comments
*   issue\_events
*   issues
*   milestones
*   organizations
*   projects
*   protected\_branches
*   pull\_request\_reviews
*   pull\_requests
*   releases
*   repositories
*   review\_comments
*   schema
*   users

The archive will also contain an `attachments` directory that includes all attachment files uploaded to GitHub.com and a `repositories` directory that contains the repository's Git data.

## Responses

| Status | Description |
|--------|-------------|
| 302 | Response |
| 304 | (reference) |
| 401 | (reference) |
| 403 | (reference) |

