# POST /accounts/{account_id}/magic/cloud/catalog-syncs

**Resource:** [Catalog Sync](../resources/Catalog-Sync.md)
**Create Catalog Sync**
**Operation ID:** `catalog-syncs-create`

Create a new Catalog Sync (Closed Beta).

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | mcn_account_id | Yes |  |
| `forwarded` | header | string | No |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [mcn_create_catalog_sync_request](../schemas/mcn/mcn-create-catalog-sync-request.md)

## Responses

| Status | Description |
|--------|-------------|
| 201 | Created. |
| 400 | Bad Request. |
| 401 | Invalid Credentials. |
| 403 | Forbidden. |
| 409 | Conflict. |
| 422 | Unprocessable Entity. |
| 500 | Internal Server Error. |

**Success Response Schema:**

[mcn_create_catalog_sync_response](../schemas/mcn/mcn-create-catalog-sync-response.md)

## Security

- **api_email**
- **api_key**
- **api_token**
