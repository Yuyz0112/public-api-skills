# POST /2010-04-01/Accounts/{AccountSid}/IncomingPhoneNumbers/{Sid}.json

**Resource:** [Api20100401IncomingPhoneNumber](../resources/Api20100401IncomingPhoneNumber.md)
**Update an incoming-phone-number instance.**
**Operation ID:** `UpdateIncomingPhoneNumber`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `AccountSid` | path | string | Yes | The SID of the [Account](https://www.twilio.com/docs/iam/api/account) that created the IncomingPhoneNumber resource to update.  For more information, see [Exchanging Numbers Between Subaccounts](https://www.twilio.com/docs/iam/api/subaccounts#exchanging-numbers). |
| `Sid` | path | string | Yes | The Twilio-provided string that uniquely identifies the IncomingPhoneNumber resource to update. |

## Request Body

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

**Success Response Schema:**

[api.v2010.account.incoming_phone_number](../schemas/api-v2010-account-incoming/api-v2010-account-incoming-phone-number.md)

## Security

- **accountSid_authToken**
