# GET /2010-04-01/Accounts/{AccountSid}/Applications/{Sid}.json

**Resource:** [Api20100401Application](../resources/Api20100401Application.md)
**Fetch the application specified by the provided sid**
**Operation ID:** `FetchApplication`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `AccountSid` | path | string | Yes | The SID of the [Account](https://www.twilio.com/docs/iam/api/account) that created the Application resource to fetch. |
| `Sid` | path | string | Yes | The Twilio-provided string that uniquely identifies the Application resource to fetch. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

**Success Response Schema:**

[api.v2010.account.application](../schemas/api-v2010-account-application/api-v2010-account-application.md)

## Security

- **accountSid_authToken**
