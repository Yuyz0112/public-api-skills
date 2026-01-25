# GET /accounts/{account_id}/access/apps/ca

**Resource:** [Access short-lived certificate CAs](../resources/Access-short-lived-certificate-CAs.md)
**List short-lived certificate CAs**
**Operation ID:** `access-short-lived-certificate-c-as-list-short-lived-certificate-c-as`

Lists short-lived certificate CAs and their public keys.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | access_identifier | Yes |  |
| `per_page` | query | integer | No |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | List short-lived certificate CAs response |
| 4XX | List short-lived certificate CAs response failure |

**Success Response Schema:**

[access_ca_components-schemas-response_collection](../schemas/access/access-ca-components-schemas-response-collection.md)

## Security

- **api_email**
- **api_key**
- **api_token**
