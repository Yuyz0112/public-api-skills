# POST /repos/{owner}/{repo}/releases/generate-notes

**Resource:** [repos](../resources/repos.md)
**Generate release notes content for a release**
**Operation ID:** `repos/generate-release-notes`

Generate a name and body describing a [release](https://docs.github.com/rest/releases/releases#get-a-release). The body content will be markdown formatted and contain information like the changes since last release and users who contributed. The generated release notes are not saved anywhere. They are intended to be generated and used when creating a new release.

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Name and body of generated release notes |
| 404 | (reference) |

**Success Response Schema:**

[release-notes-content](../schemas/release-notes-content/release-notes-content.md)

