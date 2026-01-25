# DELETE /2010-04-01/Accounts/{AccountSid}/SIP/Domains/{DomainSid}/CredentialListMappings/{Sid}.json

**Resource:** [Api20100401CredentialListMapping](../resources/Api20100401CredentialListMapping.md)
**Delete a CredentialListMapping resource from an account.**
**Operation ID:** `DeleteSipCredentialListMapping`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `AccountSid` | path | string | Yes | The unique id of the [Account](https://www.twilio.com/docs/iam/api/account) responsible for this resource. |
| `DomainSid` | path | string | Yes | A 34 character string that uniquely identifies the SIP Domain that includes the resource to delete. |
| `Sid` | path | string | Yes | A 34 character string that uniquely identifies the resource to delete. |

## Responses

| Status | Description |
|--------|-------------|
| 204 | The resource was deleted successfully. |

## Security

- **accountSid_authToken**
