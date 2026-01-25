# PUT /accounts/{account_id}/workers/dispatch/namespaces/{dispatch_namespace}

**Resource:** [Workers for Platforms](../resources/Workers-for-Platforms.md)
**Update dispatch namespace**
**Operation ID:** `namespace-worker-put-namespace`

Update a Workers for Platforms namespace.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | workers_identifier | Yes |  |
| `dispatch_namespace` | path | workers_dispatch_namespace_name | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Update a Workers for Platforms namespace. |
| 4XX | Failure to update Workers for Platforms namespace. |

**Success Response Schema:**

[workers_namespace-single-response](../schemas/workers/workers-namespace-single-response.md)

## Security

- **api_token**
- **api_email**
- **api_key**
