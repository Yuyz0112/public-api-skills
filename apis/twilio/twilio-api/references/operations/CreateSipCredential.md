# POST /2010-04-01/Accounts/{AccountSid}/SIP/CredentialLists/{CredentialListSid}/Credentials.json

**Resource:** [Api20100401Credential](../resources/Api20100401Credential.md)
**Create a new credential resource.**
**Operation ID:** `CreateSipCredential`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `AccountSid` | path | string | Yes | The unique id of the Account that is responsible for this resource. |
| `CredentialListSid` | path | string | Yes | The unique id that identifies the credential list to include the created credential. |

## Request Body

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 201 | Created |

**Success Response Schema:**

[api.v2010.account.sip.sip_credential_list.sip_credential](../schemas/api-v2010-account-sip-sip/api-v2010-account-sip-sip-credential-list-sip-credential.md)

## Security

- **accountSid_authToken**
