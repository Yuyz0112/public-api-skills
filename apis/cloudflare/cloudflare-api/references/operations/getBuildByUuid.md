# GET /accounts/{account_id}/builds/builds/{build_uuid}

**Resource:** [Builds](../resources/Builds.md)
**Get build by UUID**
**Operation ID:** `getBuildByUuid`

Retrieve detailed information about a specific build

## Responses

| Status | Description |
|--------|-------------|
| 200 | Build retrieved successfully |
| 404 | (reference) |

## Security

- **api_token**
- **api_email**
- **api_key**
