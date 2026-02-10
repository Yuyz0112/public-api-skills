# PUT /api/v4/user/{user_id}/credit_card_validation

**Resource:** [Users](../resources/Users.md)
**[DEPRECATED] Update a user's credit_card_validation**
**Operation ID:** `putApiV4UserUserIdCreditCardValidation`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `user_id` | path | string | Yes | The ID or username of the user |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

**Success Response Schema:**

[APIEntitiesUserCreditCardValidations](../schemas/APIEntitiesUserCreditCardValidations/APIEntitiesUserCreditCardValidations.md)

