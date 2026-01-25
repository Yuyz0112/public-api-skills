# PUT /zones/{zone_id}/security-center/securitytxt

**Resource:** [security.txt](../resources/security-txt.md)
**Update security.txt**
**Operation ID:** `update-security-txt`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `zone_id` | path | security-center_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [security-center_securityTxt](../schemas/security-center/security-center-securityTxt.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 4XX | Client Error |

## Security

- **api_email**
- **api_key**
- **api_token**
