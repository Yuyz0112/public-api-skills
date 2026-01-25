# GET /accounts/{account_id}/containers

**Resource:** [Containers](../resources/Containers.md)
**List containers.**
**Operation ID:** `publicListApplications`

Lists all the container applications that are associated with your account.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `name` | query | string | No | Filter containers by name |
| `image` | query | string | No | Filter containers by image |

## Responses

| Status | Description |
|--------|-------------|
| 200 | (reference) |
| 401 | (reference) |
| 500 | (reference) |

## Security

- **api_token**
- **api_email**
- **api_key**
- **api_email**
- **api_key**
