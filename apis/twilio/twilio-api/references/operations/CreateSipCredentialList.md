# POST /2010-04-01/Accounts/{AccountSid}/SIP/CredentialLists.json

**Resource:** [Api20100401CredentialList](../resources/Api20100401CredentialList.md)
**Create a Credential List**
**Operation ID:** `CreateSipCredentialList`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `AccountSid` | path | string | Yes | The unique id of the Account that is responsible for this resource. |

## Request Body

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 201 | Created |

**Success Response Schema:**

[api.v2010.account.sip.sip_credential_list](../schemas/api-v2010-account-sip-sip/api-v2010-account-sip-sip-credential-list.md)

## Security

- **accountSid_authToken**
