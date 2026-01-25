# DELETE /2010-04-01/Accounts/{AccountSid}/SIP/CredentialLists/{CredentialListSid}/Credentials/{Sid}.json

**Resource:** [Api20100401Credential](../resources/Api20100401Credential.md)
**Delete a credential resource.**
**Operation ID:** `DeleteSipCredential`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `AccountSid` | path | string | Yes | The unique id of the Account that is responsible for this resource. |
| `CredentialListSid` | path | string | Yes | The unique id that identifies the credential list that contains the desired credentials. |
| `Sid` | path | string | Yes | The unique id that identifies the resource to delete. |

## Responses

| Status | Description |
|--------|-------------|
| 204 | The resource was deleted successfully. |

## Security

- **accountSid_authToken**
