# GET /meta

**Resource:** [meta](../resources/meta.md)
**Get GitHub meta information**
**Operation ID:** `meta/get`

Returns meta information about GitHub, including a list of GitHub's IP addresses. For more information, see "[About GitHub's IP addresses](https://docs.github.com/articles/about-github-s-ip-addresses/)."

The API's response also includes a list of GitHub's domain names.

The values shown in the documentation's response are example values. You must always query the API directly to get the latest values.

> [!NOTE]
> This endpoint returns both IPv4 and IPv6 addresses. However, not all features support IPv6. You should refer to the specific documentation for each feature to determine if IPv6 is supported.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 304 | (reference) |

**Success Response Schema:**

[api-overview](../schemas/api-overview/api-overview.md)

