# PUT /accounts/{account_id}/storage/kv/namespaces/{namespace_id}/values/{key_name}

**Resource:** [Workers KV Namespace](../resources/Workers-KV-Namespace.md)
**Write key-value pair with optional metadata**
**Operation ID:** `workers-kv-namespace-write-key-value-pair-with-metadata`

Write a value identified by a key. Use URL-encoding to use special characters (for example, `:`, `!`, `%`) in the key name. Body should be the value to be stored. If JSON metadata to be associated with the key/value pair is needed, use `multipart/form-data` content type for your PUT request (see dropdown below in `REQUEST BODY SCHEMA`). Existing values, expirations, and metadata will be overwritten. If neither `expiration` nor `expiration_ttl` is specified, the key-value pair will never expire. If both are set, `expiration_ttl` is used and `expiration` is ignored.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `key_name` | path | workers-kv_key_name | Yes |  |
| `namespace_id` | path | workers-kv_namespace_identifier | Yes |  |
| `account_id` | path | workers-kv_identifier | Yes |  |
| `expiration` | query | workers-kv_expiration | No |  |
| `expiration_ttl` | query | workers-kv_expiration_ttl | No |  |

## Request Body

**Required:** Yes

**Content Types:** `application/octet-stream`, `multipart/form-data`

**Schema:** [workers-kv_value](../schemas/workers-kv/workers-kv-value.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Write key-value pair with metadata response. |
| 4XX | Write key-value pair with metadata response failure. |

**Success Response Schema:**

[workers-kv_api-response-common-no-result](../schemas/workers-kv/workers-kv-api-response-common-no-result.md)

## Security

- **api_token**
- **api_email**
- **api_key**
