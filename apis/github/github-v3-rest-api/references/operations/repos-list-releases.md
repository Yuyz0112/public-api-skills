# GET /repos/{owner}/{repo}/releases

**Resource:** [repos](../resources/repos.md)
**List releases**
**Operation ID:** `repos/list-releases`

This returns a list of releases, which does not include regular Git tags that have not been associated with a release. To get a list of Git tags, use the [Repository Tags API](https://docs.github.com/rest/repos/repos#list-repository-tags).

Information about published releases are available to everyone. Only users with push access will receive listings for draft releases.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 404 | (reference) |

**Success Response Schema:**

Array of [release](../schemas/release/release.md)

