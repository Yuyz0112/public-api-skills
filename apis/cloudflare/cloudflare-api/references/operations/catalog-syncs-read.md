# GET /accounts/{account_id}/magic/cloud/catalog-syncs/{sync_id}

**Resource:** [Catalog Sync](../resources/Catalog-Sync.md)
**Read Catalog Sync**
**Operation ID:** `catalog-syncs-read`

Read a Catalog Sync (Closed Beta).

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | mcn_account_id | Yes |  |
| `sync_id` | path | mcn_catalog_sync_id | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK. |
| 400 | Bad Request. |
| 401 | Invalid Credentials. |
| 403 | Forbidden. |
| 404 | Not Found. |
| 500 | Internal Server Error. |

**Success Response Schema:**

[mcn_read_account_catalog_sync_response](../schemas/mcn/mcn-read-account-catalog-sync-response.md)

## Security

- **api_email**
- **api_key**
- **api_token**
