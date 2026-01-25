# GET /repos/{owner}/{repo}/releases/assets/{asset_id}

**Resource:** [repos](../resources/repos.md)
**Get a release asset**
**Operation ID:** `repos/get-release-asset`

To download the asset's binary content:

- If within a browser, fetch the location specified in the `browser_download_url` key provided in the response.
- Alternatively, set the `Accept` header of the request to 
  [`application/octet-stream`](https://docs.github.com/rest/using-the-rest-api/getting-started-with-the-rest-api#media-types). 
  The API will either redirect the client to the location, or stream it directly if possible.
  API clients should handle both a `200` or `302` response.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 302 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

[release-asset](../schemas/release-asset/release-asset.md)

