# PUT /accounts/{account_id}/workers/dispatch/namespaces/{dispatch_namespace}/scripts/{script_name}/secrets

**Resource:** [Workers for Platforms](../resources/Workers-for-Platforms.md)
**Add script secret**
**Operation ID:** `namespace-worker-put-script-secrets`

Add a secret to a script uploaded to a Workers for Platforms namespace.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | workers_identifier | Yes |  |
| `dispatch_namespace` | path | workers_dispatch_namespace_name | Yes |  |
| `script_name` | path | workers_script_name | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [workers_secret](../schemas/workers/workers-secret.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Fetch script bindings (Workers for Platforms). |
| 4XX | Fetch script bindings failure (Workers for Platforms). |

## Security

- **api_token**
- **api_email**
- **api_key**
