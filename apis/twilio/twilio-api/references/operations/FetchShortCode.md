# GET /2010-04-01/Accounts/{AccountSid}/SMS/ShortCodes/{Sid}.json

**Resource:** [Api20100401ShortCode](../resources/Api20100401ShortCode.md)
**Fetch an instance of a short code**
**Operation ID:** `FetchShortCode`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `AccountSid` | path | string | Yes | The SID of the [Account](https://www.twilio.com/docs/iam/api/account) that created the ShortCode resource(s) to fetch. |
| `Sid` | path | string | Yes | The Twilio-provided string that uniquely identifies the ShortCode resource to fetch |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

**Success Response Schema:**

[api.v2010.account.short_code](../schemas/api-v2010-account-short/api-v2010-account-short-code.md)

## Security

- **accountSid_authToken**
