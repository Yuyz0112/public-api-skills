# POST /accounts/{account_id}/cloudforce-one/events/relationships/create

**Resource:** [Event](../resources/Event.md)
**Create a relationship between two events**
**Operation ID:** `post_CreateEventRelationship`

Creates a directed relationship between two events. The relationship is from parent to child with a specified type.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | string | Yes | Account ID. |

## Request Body

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Relationship created successfully |
| 400 | Bad Request. |

## Security

- **api_token**
