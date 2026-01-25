# GET /2/media/analytics

**Resource:** [Media](../resources/Media.md)
**Get Media analytics**
**Operation ID:** `getMediaAnalytics`

Retrieves analytics data for media.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `media_keys` | query | MediaKey[] | Yes | A comma separated list of Media Keys. Up to 100 are allowed in a single request. |
| `end_time` | query | string (date-time) | Yes | YYYY-MM-DDTHH:mm:ssZ. The UTC timestamp representing the end of the time range. |
| `start_time` | query | string (date-time) | Yes | YYYY-MM-DDTHH:mm:ssZ. The UTC timestamp representing the start of the time range. |
| `granularity` | query | enum: hourly, daily, total | Yes | The granularity for the search counts results. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | The request has succeeded. |
| default | The request has failed. |

**Success Response Schema:**

[MediaAnalytics](../schemas/Media/MediaAnalytics.md)

## Security

- **OAuth2UserToken**: tweet.read
- **UserToken**
