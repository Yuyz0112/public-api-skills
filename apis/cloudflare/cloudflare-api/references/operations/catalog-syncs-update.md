# PUT /accounts/{account_id}/magic/cloud/catalog-syncs/{sync_id}

**Resource:** [Catalog Sync](../resources/Catalog-Sync.md)
**Update Catalog Sync**
**Operation ID:** `catalog-syncs-update`

Update a Catalog Sync (Closed Beta).

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | mcn_account_id | Yes |  |
| `sync_id` | path | mcn_catalog_sync_id | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [mcn_update_catalog_sync_request](../schemas/mcn/mcn-update-catalog-sync-request.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK. |
| 400 | Bad Request. |
| 401 | Invalid Credentials. |
| 403 | Forbidden. |
| 404 | Not Found. |
| 409 | Conflict. |
| 422 | Unprocessable Entity. |
| 500 | Internal Server Error. |

**Success Response Schema:**

[mcn_update_catalog_sync_response](../schemas/mcn/mcn-update-catalog-sync-response.md)

## Security

- **api_email**
- **api_key**
- **api_token**
