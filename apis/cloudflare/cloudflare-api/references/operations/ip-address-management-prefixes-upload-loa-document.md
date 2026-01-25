# POST /accounts/{account_id}/addressing/loa_documents

**Resource:** [IP Address Management Prefixes](../resources/IP-Address-Management-Prefixes.md)
**Upload LOA Document**
**Operation ID:** `ip-address-management-prefixes-upload-loa-document`

Submit LOA document (pdf format) under the account.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | addressing_account_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `multipart/form-data`

## Responses

| Status | Description |
|--------|-------------|
| 201 | Upload LOA Document response |
| 4XX | Upload LOA Document response failure |

**Success Response Schema:**

[addressing_loa_upload_response](../schemas/addressing/addressing-loa-upload-response.md)

## Security

- **api_email**
- **api_key**
