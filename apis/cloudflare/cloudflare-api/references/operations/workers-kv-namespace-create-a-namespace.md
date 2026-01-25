# POST /accounts/{account_id}/storage/kv/namespaces

**Resource:** [Workers KV Namespace](../resources/Workers-KV-Namespace.md)
**Create a Namespace**
**Operation ID:** `workers-kv-namespace-create-a-namespace`

Creates a namespace under the given title. A `400` is returned if the account already owns a namespace with this title. A namespace must be explicitly deleted to be replaced.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | workers-kv_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [workers-kv_create_rename_namespace_body](../schemas/workers-kv/workers-kv-create-rename-namespace-body.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Create a Namespace response. |
| 4XX | Create a Namespace response failure. |

## Security

- **api_token**
- **api_email**
- **api_key**
