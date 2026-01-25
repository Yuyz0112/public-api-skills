# GET /v1/identity/verification_reports/{report}

**Resource:** [identity](../resources/identity.md)
**Retrieve a VerificationReport**
**Operation ID:** `GetIdentityVerificationReportsReport`

<p>Retrieves an existing VerificationReport</p>

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `expand` | query | string[] | No | Specifies which fields in the response should be expanded. |
| `report` | path | string | Yes |  |

## Request Body

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| default | Error response. |

**Success Response Schema:**

[identity.verification_report](../schemas/identity-verification/identity-verification-report.md)

