# GET /2010-04-01/Accounts/{AccountSid}/Calls/{Sid}.json

**Resource:** [Api20100401Call](../resources/Api20100401Call.md)
**Fetch the call specified by the provided Call SID**
**Operation ID:** `FetchCall`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `AccountSid` | path | string | Yes | The SID of the [Account](https://www.twilio.com/docs/iam/api/account) that created the Call resource(s) to fetch. |
| `Sid` | path | string | Yes | The SID of the Call resource to fetch. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

**Success Response Schema:**

[api.v2010.account.call](../schemas/api-v2010-account-call/api-v2010-account-call.md)

## Security

- **accountSid_authToken**
