# DELETE /2010-04-01/Accounts/{AccountSid}/SIP/CredentialLists/{Sid}.json

**Resource:** [Api20100401CredentialList](../resources/Api20100401CredentialList.md)
**Delete a Credential List**
**Operation ID:** `DeleteSipCredentialList`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `AccountSid` | path | string | Yes | The unique id of the Account that is responsible for this resource. |
| `Sid` | path | string | Yes | The credential list Sid that uniquely identifies this resource |

## Responses

| Status | Description |
|--------|-------------|
| 204 | The resource was deleted successfully. |

## Security

- **accountSid_authToken**
