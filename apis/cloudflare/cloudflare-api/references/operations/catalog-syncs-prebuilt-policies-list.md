# GET /accounts/{account_id}/magic/cloud/catalog-syncs/prebuilt-policies

**Resource:** [Catalog Sync](../resources/Catalog-Sync.md)
**List Prebuilt Policies**
**Operation ID:** `catalog-syncs-prebuilt-policies-list`

List prebuilt catalog sync policies (Closed Beta).

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | mcn_account_id | Yes |  |
| `destination_type` | query | mcn_catalog_sync_destination_type | No | Specify type of destination, omit to return all. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK. |
| 400 | Bad Request. |
| 401 | Invalid Credentials. |
| 403 | Forbidden. |
| 500 | Internal Server Error. |

**Success Response Schema:**

[mcn_catalog_syncs_prebuilt_policies_response](../schemas/mcn/mcn-catalog-syncs-prebuilt-policies-response.md)

## Security

- **api_email**
- **api_key**
- **api_token**
