# POST /accounts/{account_id}/browser-rendering/snapshot

**Resource:** [brapi](../resources/brapi.md)
**Get HTML content and screenshot.**
**Operation ID:** `brapi-post_Snapshot`

Returns the page's HTML content and screenshot. Control page loading with `gotoOptions` and `waitFor*` options. Customize screenshots with `viewport`, `fullPage`, `clip` and others.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | string | Yes | Account ID. |
| `cacheTTL` | query | number | No | Cache TTL default is 5s. Set to 0 to disable. |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returns the screenshot |
| 400 | The request contains errors or didn't properly encode content. |
| 422 | Request failed due to site-related issues such as timeouts, SSL errors, or inaccessible content. |
| 429 | Request failed due to rate limiting. The Retry-After header indicates when the client should retry the request. |
| 500 | Internal server error |

## Security

- **api_email**
- **api_key**
- **api_token**
