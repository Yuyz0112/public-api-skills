# POST /accounts/{account_id}/cloudforce-one/binary

**Resource:** [BinDB](../resources/BinDB.md)
**Posts a file to Binary Storage**
**Operation ID:** `post_BinDBPost`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | number | Yes | Account ID. |

## Request Body

Binary file to be uploaded to the database.

**Required:** Yes

**Content Types:** `multipart/form-data`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returns file information |
| 400 | Bad Request. |

## Security

- **api_token**
