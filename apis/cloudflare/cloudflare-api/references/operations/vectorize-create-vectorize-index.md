# POST /accounts/{account_id}/vectorize/v2/indexes

**Resource:** [Vectorize](../resources/Vectorize.md)
**Create Vectorize Index**
**Operation ID:** `vectorize-create-vectorize-index`

Creates and returns a new Vectorize Index.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | vectorize_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [vectorize_create-index-request](../schemas/vectorize/vectorize-create-index-request.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Create Vectorize Index Response |
| 4XX | Create Vectorize Index Failure Response |

## Security

- **api_token**
- **api_email**
- **api_key**
