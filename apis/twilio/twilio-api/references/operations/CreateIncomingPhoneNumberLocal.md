# POST /2010-04-01/Accounts/{AccountSid}/IncomingPhoneNumbers/Local.json

**Resource:** [Api20100401IncomingPhoneNumberLocal](../resources/Api20100401IncomingPhoneNumberLocal.md)
**Operation ID:** `CreateIncomingPhoneNumberLocal`

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

[api.v2010.account.incoming_phone_number.incoming_phone_number_local](../schemas/api-v2010-account-incoming/api-v2010-account-incoming-phone-number-incoming-phone-number-local.md)

## Security

- **accountSid_authToken**
