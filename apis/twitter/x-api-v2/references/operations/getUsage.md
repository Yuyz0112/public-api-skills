# GET /2/usage/tweets

**Resource:** [Usage](../resources/Usage.md)
**Get usage**
**Operation ID:** `getUsage`

Retrieves usage statistics for Posts over a specified number of days.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `days` | query | integer (int32) | No | The number of days for which you need usage for. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | The request has succeeded. |
| default | The request has failed. |

**Success Response Schema:**

[Get2UsageTweetsResponse](../schemas/Get/Get2UsageTweetsResponse.md)

## Security

- **BearerToken**
