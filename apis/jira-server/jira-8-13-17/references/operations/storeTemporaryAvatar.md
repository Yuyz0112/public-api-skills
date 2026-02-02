# POST /avatar/{type}/temporary

**Resource:** [avatar](../resources/avatar.md)
**Operation ID:** `storeTemporaryAvatar`

Creates temporary avatar

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `filename` | query | string | No | name of file being uploaded |
| `size` | query | integer (int64) | No | size of file |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful Response |

