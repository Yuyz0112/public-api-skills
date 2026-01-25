# GET /2010-04-01/Accounts/{AccountSid}/Balance.json

**Resource:** [Api20100401Balance](../resources/Api20100401Balance.md)
**Fetch the balance for an Account based on Account Sid. Balance changes may not be reflected immediately. Child accounts do not contain balance information**
**Operation ID:** `FetchBalance`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `AccountSid` | path | string | Yes | The unique SID identifier of the Account. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

**Success Response Schema:**

[api.v2010.account.balance](../schemas/api-v2010-account-balance/api-v2010-account-balance.md)

## Security

- **accountSid_authToken**
