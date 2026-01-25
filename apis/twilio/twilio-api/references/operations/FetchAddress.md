# GET /2010-04-01/Accounts/{AccountSid}/Addresses/{Sid}.json

**Resource:** [Api20100401Address](../resources/Api20100401Address.md)
**Operation ID:** `FetchAddress`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `AccountSid` | path | string | Yes | The SID of the [Account](https://www.twilio.com/docs/iam/api/account) that is responsible for the Address resource to fetch. |
| `Sid` | path | string | Yes | The Twilio-provided string that uniquely identifies the Address resource to fetch. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

**Success Response Schema:**

[api.v2010.account.address](../schemas/api-v2010-account-address/api-v2010-account-address.md)

## Security

- **accountSid_authToken**
