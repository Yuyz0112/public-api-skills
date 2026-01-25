# GET /repositories

**Resource:** [repos](../resources/repos.md)
**List public repositories**
**Operation ID:** `repos/list-public`

Lists all public repositories in the order that they were created.

Note:
- For GitHub Enterprise Server, this endpoint will only list repositories available to all users on the enterprise.
- Pagination is powered exclusively by the `since` parameter. Use the [Link header](https://docs.github.com/rest/guides/using-pagination-in-the-rest-api#using-link-headers) to get the URL for the next page of repositories.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 304 | (reference) |
| 422 | (reference) |

**Success Response Schema:**

Array of [minimal-repository](../schemas/minimal-repository/minimal-repository.md)

