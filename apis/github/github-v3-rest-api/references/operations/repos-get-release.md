# GET /repos/{owner}/{repo}/releases/{release_id}

**Resource:** [repos](../resources/repos.md)
**Get a release**
**Operation ID:** `repos/get-release`

Gets a public release with the specified release ID.

> [!NOTE]
> This returns an `upload_url` key corresponding to the endpoint for uploading release assets. This key is a hypermedia resource. For more information, see "[Getting started with the REST API](https://docs.github.com/rest/using-the-rest-api/getting-started-with-the-rest-api#hypermedia)."

## Responses

| Status | Description |
|--------|-------------|
| 200 | **Note:** This returns an `upload_url` key corresponding to the endpoint for uploading release assets. This key is a hypermedia resource. For more information, see "[Getting started with the REST API](https://docs.github.com/rest/using-the-rest-api/getting-started-with-the-rest-api#hypermedia)." |
| 401 | Unauthorized |

**Success Response Schema:**

[release](../schemas/release/release.md)

