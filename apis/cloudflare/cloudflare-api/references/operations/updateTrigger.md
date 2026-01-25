# PATCH /accounts/{account_id}/builds/triggers/{trigger_uuid}

**Resource:** [Triggers](../resources/Triggers.md)
**Update trigger**
**Operation ID:** `updateTrigger`

Update an existing CI/CD trigger

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [builds_UpdateTriggerRequest](../schemas/builds/builds-UpdateTriggerRequest.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Trigger updated successfully |
| 404 | (reference) |

## Security

- **api_token**
- **api_email**
- **api_key**
