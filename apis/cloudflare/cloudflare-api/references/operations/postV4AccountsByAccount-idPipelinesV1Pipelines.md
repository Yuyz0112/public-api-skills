# POST /accounts/{account_id}/pipelines/v1/pipelines

**Resource:** [workers_pipelines_other](../resources/workers-pipelines-other.md)
**Create Pipeline**
**Operation ID:** `postV4AccountsByAccount_idPipelinesV1Pipelines`

Create a new Pipeline.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | cloudflare-pipelines_workers-pipelines-account-id | Yes |  |

## Request Body

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Indicates a successfully created Pipeline. |
| 4XX | Indicates an error in creating a Pipeline. |

## Security

- **api_token**
- **api_email**
- **api_key**
