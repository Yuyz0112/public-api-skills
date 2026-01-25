# GET /accounts/{account_id}/addressing/loa_documents/{loa_document_id}/download

**Resource:** [IP Address Management Prefixes](../resources/IP-Address-Management-Prefixes.md)
**Download LOA Document**
**Operation ID:** `ip-address-management-prefixes-download-loa-document`

Download specified LOA document under the account.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `loa_document_id` | path | addressing_loa_document_identifier | Yes |  |
| `account_id` | path | addressing_account_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Download LOA Document response |
| 4XX | Download LOA Document response failure |

## Security

- **api_email**
- **api_key**
