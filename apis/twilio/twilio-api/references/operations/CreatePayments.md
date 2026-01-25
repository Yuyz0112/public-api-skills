# POST /2010-04-01/Accounts/{AccountSid}/Calls/{CallSid}/Payments.json

**Resource:** [Api20100401Payment](../resources/Api20100401Payment.md)
**create an instance of payments. This will start a new payments session**
**Operation ID:** `CreatePayments`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `AccountSid` | path | string | Yes | The SID of the [Account](https://www.twilio.com/docs/iam/api/account) that will create the resource. |
| `CallSid` | path | string | Yes | The SID of the call that will create the resource. Call leg associated with this sid is expected to provide payment information thru DTMF. |

## Request Body

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 201 | Created |

**Success Response Schema:**

[api.v2010.account.call.payments](../schemas/api-v2010-account-call-payments/api-v2010-account-call-payments.md)

## Security

- **accountSid_authToken**
