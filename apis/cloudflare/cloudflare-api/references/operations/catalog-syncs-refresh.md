# POST /accounts/{account_id}/magic/cloud/catalog-syncs/{sync_id}/refresh

**Resource:** [Catalog Sync](../resources/Catalog-Sync.md)
**Run Catalog Sync**
**Operation ID:** `catalog-syncs-refresh`

Refresh a Catalog Sync's destination by running the sync policy against latest resource catalog (Closed Beta).

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
| 409 | Conflict. |
| 422 | Unprocessable Entity. |
| 500 | Internal Server Error. |

**Success Response Schema:**

[mcn_refresh_catalog_sync_response](../schemas/mcn/mcn-refresh-catalog-sync-response.md)

## Security

- **api_email**
- **api_key**
- **api_token**
