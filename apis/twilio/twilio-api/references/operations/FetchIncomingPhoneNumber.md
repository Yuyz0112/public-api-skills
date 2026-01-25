# GET /2010-04-01/Accounts/{AccountSid}/IncomingPhoneNumbers/{Sid}.json

**Resource:** [Api20100401IncomingPhoneNumber](../resources/Api20100401IncomingPhoneNumber.md)
**Fetch an incoming-phone-number belonging to the account used to make the request.**
**Operation ID:** `FetchIncomingPhoneNumber`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `AccountSid` | path | string | Yes | The SID of the [Account](https://www.twilio.com/docs/iam/api/account) that created the IncomingPhoneNumber resource to fetch. |
| `Sid` | path | string | Yes | The Twilio-provided string that uniquely identifies the IncomingPhoneNumber resource to fetch. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

**Success Response Schema:**

[api.v2010.account.incoming_phone_number](../schemas/api-v2010-account-incoming/api-v2010-account-incoming-phone-number.md)

## Security

- **accountSid_authToken**
