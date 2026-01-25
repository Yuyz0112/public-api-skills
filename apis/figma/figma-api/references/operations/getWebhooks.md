# GET /v2/webhooks

**Resource:** [Webhooks](../resources/Webhooks.md)
**Get webhooks by context or plan**
**Operation ID:** `getWebhooks`

Returns a list of webhooks corresponding to the context or plan provided, if they exist. For plan, the webhooks for all contexts that you have access to will be returned, and theresponse is paginated

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `context` | query | string | No | Context to create the resource on. Should be "team", "project", or "file". |
| `context_id` | query | string | No | The id of the context that you want to get attached webhooks for. If you're using context_id, you cannot use plan_api_id. |
| `plan_api_id` | query | string | No | The id of your plan. Use this to get all webhooks for all contexts you have access to. If you're using plan_api_id, you cannot use context or context_id. When you use plan_api_id, the response is paginated. |
| `cursor` | query | string | No | If you're using plan_api_id, this is the cursor to use for pagination. If you're using context or context_id, this parameter is ignored. Provide the next_page or prev_page value from the previous response to get the next or previous page of results. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | (reference) |
| 400 | (reference) |
| 403 | (reference) |

## Security

- **PersonalAccessToken**
- **OAuth2**: webhooks:read
