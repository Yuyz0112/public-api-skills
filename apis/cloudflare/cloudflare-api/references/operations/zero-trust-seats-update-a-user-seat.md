# PATCH /accounts/{account_id}/access/seats

**Resource:** [Zero Trust seats](../resources/Zero-Trust-seats.md)
**Update a user seat**
**Operation ID:** `zero-trust-seats-update-a-user-seat`

Removes a user from a Zero Trust seat when both `access_seat` and `gateway_seat` are set to false.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | access_schemas-identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [access_seats_definition](../schemas/access/access-seats-definition.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Update a user seat response |
| 4XX | Update a user seat response failure |

**Success Response Schema:**

[access_seats_components-schemas-response_collection](../schemas/access/access-seats-components-schemas-response-collection.md)

## Security

- **api_email**
- **api_key**
- **api_token**
