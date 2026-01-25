# POST /2010-04-01/Accounts/{AccountSid}/IncomingPhoneNumbers.json

**Resource:** [Api20100401IncomingPhoneNumber](../resources/Api20100401IncomingPhoneNumber.md)
**Purchase a phone-number for the account.**
**Operation ID:** `CreateIncomingPhoneNumber`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `AccountSid` | path | string | Yes | The SID of the [Account](https://www.twilio.com/docs/iam/api/account) that will create the resource. |

## Request Body

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 201 | Created |

**Success Response Schema:**

[api.v2010.account.incoming_phone_number](../schemas/api-v2010-account-incoming/api-v2010-account-incoming-phone-number.md)

## Security

- **accountSid_authToken**
