# POST /accounts/{account_id}/cloudforce-one/events/dataset/create

**Resource:** [Dataset](../resources/Dataset.md)
**Creates a dataset**
**Operation ID:** `post_DatasetCreate`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | string | Yes | Account ID. |

## Request Body

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returns dataset information. |
| 400 | Bad Request. |

## Security

- **api_token**
