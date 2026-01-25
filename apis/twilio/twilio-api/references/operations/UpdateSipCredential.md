# POST /2010-04-01/Accounts/{AccountSid}/SIP/CredentialLists/{CredentialListSid}/Credentials/{Sid}.json

**Resource:** [Api20100401Credential](../resources/Api20100401Credential.md)
**Update a credential resource.**
**Operation ID:** `UpdateSipCredential`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `AccountSid` | path | string | Yes | The unique id of the Account that is responsible for this resource. |
| `CredentialListSid` | path | string | Yes | The unique id that identifies the credential list that includes this credential. |
| `Sid` | path | string | Yes | The unique id that identifies the resource to update. |

## Request Body

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

**Success Response Schema:**

[api.v2010.account.sip.sip_credential_list.sip_credential](../schemas/api-v2010-account-sip-sip/api-v2010-account-sip-sip-credential-list-sip-credential.md)

## Security

- **accountSid_authToken**
