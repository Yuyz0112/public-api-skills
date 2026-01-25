# PUT /accounts/{account_id}/builds/builds/{build_uuid}/cancel

**Resource:** [Builds](../resources/Builds.md)
**Cancel build**
**Operation ID:** `cancelBuildByUuid`

Cancel a running or queued build

## Responses

| Status | Description |
|--------|-------------|
| 200 | Build canceled successfully |
| 404 | (reference) |

## Security

- **api_token**
- **api_email**
- **api_key**
