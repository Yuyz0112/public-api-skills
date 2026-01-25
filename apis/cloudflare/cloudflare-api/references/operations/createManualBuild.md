# POST /accounts/{account_id}/builds/triggers/{trigger_uuid}/builds

**Resource:** [Triggers](../resources/Triggers.md)
**Create manual build**
**Operation ID:** `createManualBuild`

Trigger a manual build for a specific trigger

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [builds_CreateBuildRequest](../schemas/builds/builds-CreateBuildRequest.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Build created successfully |

## Security

- **api_token**
- **api_email**
- **api_key**
