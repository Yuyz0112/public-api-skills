# POST /2010-04-01/Accounts/{AccountSid}/Calls/{CallSid}/Payments/{Sid}.json

**Resource:** [Api20100401Payment](../resources/Api20100401Payment.md)
**update an instance of payments with different phases of payment flows.**
**Operation ID:** `UpdatePayments`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `AccountSid` | path | string | Yes | The SID of the [Account](https://www.twilio.com/docs/iam/api/account) that will update the resource. |
| `CallSid` | path | string | Yes | The SID of the call that will update the resource. This should be the same call sid that was used to create payments resource. |
| `Sid` | path | string | Yes | The SID of Payments session that needs to be updated. |

## Request Body

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 202 | Accepted |

## Security

- **accountSid_authToken**
