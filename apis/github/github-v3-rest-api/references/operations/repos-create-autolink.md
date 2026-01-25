# POST /repos/{owner}/{repo}/autolinks

**Resource:** [repos](../resources/repos.md)
**Create an autolink reference for a repository**
**Operation ID:** `repos/create-autolink`

Users with admin access to the repository can create an autolink.

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 201 | response |
| 422 | (reference) |

**Success Response Schema:**

[autolink](../schemas/autolink/autolink.md)

