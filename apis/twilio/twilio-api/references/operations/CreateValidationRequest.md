# POST /2010-04-01/Accounts/{AccountSid}/OutgoingCallerIds.json

**Resource:** [Api20100401ValidationRequest](../resources/Api20100401ValidationRequest.md)
**Operation ID:** `CreateValidationRequest`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `AccountSid` | path | string | Yes | The SID of the [Account](https://www.twilio.com/docs/iam/api/account) responsible for the new caller ID resource. |

## Request Body

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

**Success Response Schema:**

[api.v2010.account.validation_request](../schemas/api-v2010-account-validation/api-v2010-account-validation-request.md)

## Security

- **accountSid_authToken**
