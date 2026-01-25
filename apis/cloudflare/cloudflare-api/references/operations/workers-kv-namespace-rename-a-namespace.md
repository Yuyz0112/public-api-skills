# PUT /accounts/{account_id}/storage/kv/namespaces/{namespace_id}

**Resource:** [Workers KV Namespace](../resources/Workers-KV-Namespace.md)
**Rename a Namespace**
**Operation ID:** `workers-kv-namespace-rename-a-namespace`

Modifies a namespace's title.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `namespace_id` | path | workers-kv_namespace_identifier | Yes |  |
| `account_id` | path | workers-kv_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [workers-kv_create_rename_namespace_body](../schemas/workers-kv/workers-kv-create-rename-namespace-body.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Rename a Namespace response. |
| 4XX | Rename a Namespace response failure. |

## Security

- **api_token**
- **api_email**
- **api_key**
