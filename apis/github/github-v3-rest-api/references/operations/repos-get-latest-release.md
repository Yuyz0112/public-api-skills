# GET /repos/{owner}/{repo}/releases/latest

**Resource:** [repos](../resources/repos.md)
**Get the latest release**
**Operation ID:** `repos/get-latest-release`

View the latest published full release for the repository.

The latest release is the most recent non-prerelease, non-draft release, sorted by the `created_at` attribute. The `created_at` attribute is the date of the commit used for the release, and not the date when the release was drafted or published.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |

**Success Response Schema:**

[release](../schemas/release/release.md)

