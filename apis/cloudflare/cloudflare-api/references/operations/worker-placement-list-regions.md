# GET /accounts/{account_id}/workers/placement/regions

**Resource:** [Worker Placement](../resources/Worker-Placement.md)
**List Placement Regions**
**Operation ID:** `worker-placement-list-regions`

Returns a list of available placement regions organized by cloud provider. These regions can be used to configure Smart Placement for Workers.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | workers_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | List Placement Regions response. |
| 4XX | List Placement Regions response failure. |

## Security

- **api_token**
- **api_email**
- **api_key**
