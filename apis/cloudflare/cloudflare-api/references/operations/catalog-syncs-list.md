# GET /accounts/{account_id}/magic/cloud/catalog-syncs

**Resource:** [Catalog Sync](../resources/Catalog-Sync.md)
**List Catalog Syncs**
**Operation ID:** `catalog-syncs-list`

List Catalog Syncs (Closed Beta).

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | mcn_account_id | Yes |  |

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

[mcn_read_account_catalog_syncs_response](../schemas/mcn/mcn-read-account-catalog-syncs-response.md)

## Security

- **api_email**
- **api_key**
- **api_token**
