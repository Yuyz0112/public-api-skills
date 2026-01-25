# POST /accounts/{account_id}/cloudforce-one/v2/events/graphql

**Resource:** [Event](../resources/Event.md)
**GraphQL endpoint for event aggregation**
**Operation ID:** `post_EventGraphQL`

Execute GraphQL aggregations over threat events. Supports multi-dimensional group-bys, optional date range filtering, and multi-dataset aggregation.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | string | Yes | Account ID. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | GraphQL response payload (data and errors). |
| 400 | Bad Request. |

## Security

- **api_token**
