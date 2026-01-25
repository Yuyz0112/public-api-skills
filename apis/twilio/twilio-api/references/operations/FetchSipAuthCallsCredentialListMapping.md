# GET /2010-04-01/Accounts/{AccountSid}/SIP/Domains/{DomainSid}/Auth/Calls/CredentialListMappings/{Sid}.json

**Resource:** [Api20100401AuthCallsCredentialListMapping](../resources/Api20100401AuthCallsCredentialListMapping.md)
**Fetch a specific instance of a credential list mapping**
**Operation ID:** `FetchSipAuthCallsCredentialListMapping`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `AccountSid` | path | string | Yes | The SID of the [Account](https://www.twilio.com/docs/iam/api/account) that created the CredentialListMapping resource to fetch. |
| `DomainSid` | path | string | Yes | The SID of the SIP domain that contains the resource to fetch. |
| `Sid` | path | string | Yes | The Twilio-provided string that uniquely identifies the CredentialListMapping resource to fetch. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

**Success Response Schema:**

[api.v2010.account.sip.sip_domain.sip_auth.sip_auth_calls.sip_auth_calls_credential_list_mapping](../schemas/api-v2010-account-sip-sip/api-v2010-account-sip-sip-domain-sip-auth-sip-auth-calls-sip-auth-calls-credential-list-mapping.md)

## Security

- **accountSid_authToken**
