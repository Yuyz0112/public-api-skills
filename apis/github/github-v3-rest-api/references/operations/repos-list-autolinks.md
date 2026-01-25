# GET /repos/{owner}/{repo}/autolinks

**Resource:** [repos](../resources/repos.md)
**Get all autolinks of a repository**
**Operation ID:** `repos/list-autolinks`

Gets all autolinks that are configured for a repository.

Information about autolinks are only available to repository administrators.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |

**Success Response Schema:**

Array of [autolink](../schemas/autolink/autolink.md)

