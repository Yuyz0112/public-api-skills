# POST /accounts/{account_id}/builds/triggers

**Resource:** [Triggers](../resources/Triggers.md)
**Create trigger**
**Operation ID:** `createTrigger`

Create a new CI/CD trigger

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [builds_CreateTriggerRequest](../schemas/builds/builds-CreateTriggerRequest.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Trigger created successfully |

## Security

- **api_token**
- **api_email**
- **api_key**
