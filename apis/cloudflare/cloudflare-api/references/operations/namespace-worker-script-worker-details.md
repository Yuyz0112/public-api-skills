# GET /accounts/{account_id}/workers/dispatch/namespaces/{dispatch_namespace}/scripts/{script_name}

**Resource:** [Workers for Platforms](../resources/Workers-for-Platforms.md)
**Worker Details**
**Operation ID:** `namespace-worker-script-worker-details`

Fetch information about a script uploaded to a Workers for Platforms namespace.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | workers_identifier | Yes |  |
| `dispatch_namespace` | path | workers_dispatch_namespace_name | Yes |  |
| `script_name` | path | workers_script_name | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Worker Details Response (Workers for Platforms). |
| 4XX | Worker Details Failure (Workers for Platforms). |

**Success Response Schema:**

[workers_namespace-script-response-single](../schemas/workers/workers-namespace-script-response-single.md)

## Security

- **api_token**
- **api_email**
- **api_key**
