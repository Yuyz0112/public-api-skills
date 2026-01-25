# POST /zones/{zone_id}/custom_hostnames

**Resource:** [Custom Hostname for a Zone](../resources/Custom-Hostname-for-a-Zone.md)
**Create Custom Hostname**
**Operation ID:** `custom-hostname-for-a-zone-create-custom-hostname`

Add a new custom hostname and request that an SSL certificate be issued for it. One of three validation methods—http, txt, email—should be used, with 'http' recommended if the CNAME is already in place (or will be soon). Specifying 'email' will send an email to the WHOIS contacts on file for the base domain plus hostmaster, postmaster, webmaster, admin, administrator. If http is used and the domain is not already pointing to the Managed CNAME host, the PATCH method must be used once it is (to complete validation).  Enable bundling of certificates using the custom_cert_bundle field. The bundling process requires the following condition One certificate in the bundle must use an RSA, and the other must use an ECDSA.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `zone_id` | path | tls-certificates-and-hostnames_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Create Custom Hostname response |
| 4XX | Create Custom Hostname response failure |

**Success Response Schema:**

[tls-certificates-and-hostnames_custom_hostname_response_single](../schemas/tls-certificates-and-hostnames/tls-certificates-and-hostnames-custom-hostname-response-single.md)

## Security

- **api_email**
- **api_key**
- **api_token**
