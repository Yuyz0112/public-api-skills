# GET /2010-04-01/Accounts/{AccountSid}/SigningKeys/{Sid}.json

**Resource:** [Api20100401SigningKey](../resources/Api20100401SigningKey.md)
**Operation ID:** `FetchSigningKey`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `AccountSid` | path | string | Yes |  |
| `Sid` | path | string | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

**Success Response Schema:**

[api.v2010.account.signing_key](../schemas/api-v2010-account-signing/api-v2010-account-signing-key.md)

## Security

- **accountSid_authToken**
