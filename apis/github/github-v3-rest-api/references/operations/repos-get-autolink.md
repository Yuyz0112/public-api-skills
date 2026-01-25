# GET /repos/{owner}/{repo}/autolinks/{autolink_id}

**Resource:** [repos](../resources/repos.md)
**Get an autolink reference of a repository**
**Operation ID:** `repos/get-autolink`

This returns a single autolink reference by ID that was configured for the given repository.

Information about autolinks are only available to repository administrators.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 404 | (reference) |

**Success Response Schema:**

[autolink](../schemas/autolink/autolink.md)

