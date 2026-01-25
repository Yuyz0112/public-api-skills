# GET /v1/confirmation_tokens/{confirmation_token}

**Resource:** [confirmation_tokens](../resources/confirmation-tokens.md)
**Retrieve a ConfirmationToken**
**Operation ID:** `GetConfirmationTokensConfirmationToken`

<p>Retrieves an existing ConfirmationToken object</p>

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `confirmation_token` | path | string | Yes |  |
| `expand` | query | string[] | No | Specifies which fields in the response should be expanded. |

## Request Body

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| default | Error response. |

**Success Response Schema:**

[confirmation_token](../schemas/confirmation/confirmation-token.md)

