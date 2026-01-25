# GET /2010-04-01/Accounts/{AccountSid}/SIP/Domains/{DomainSid}/CredentialListMappings/{Sid}.json

**Resource:** [Api20100401CredentialListMapping](../resources/Api20100401CredentialListMapping.md)
**Fetch a single CredentialListMapping resource from an account.**
**Operation ID:** `FetchSipCredentialListMapping`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `AccountSid` | path | string | Yes | The unique id of the [Account](https://www.twilio.com/docs/iam/api/account) responsible for this resource. |
| `DomainSid` | path | string | Yes | A 34 character string that uniquely identifies the SIP Domain that includes the resource to fetch. |
| `Sid` | path | string | Yes | A 34 character string that uniquely identifies the resource to fetch. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

**Success Response Schema:**

[api.v2010.account.sip.sip_domain.sip_credential_list_mapping](../schemas/api-v2010-account-sip-sip/api-v2010-account-sip-sip-domain-sip-credential-list-mapping.md)

## Security

- **accountSid_authToken**
