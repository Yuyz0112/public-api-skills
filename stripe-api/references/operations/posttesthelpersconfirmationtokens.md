# POST /v1/test_helpers/confirmation_tokens

**Resource:** [test_helpers](../resources/test-helpers.md)
**Create a test Confirmation Token**
**Operation ID:** `PostTestHelpersConfirmationTokens`

<p>Creates a test mode Confirmation Token server side for your integration tests.</p>

## Request Body

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| default | Error response. |

**Success Response Schema:**

[confirmation_token](../schemas/confirmation/confirmation-token.md)

