# POST /accounts/{account_id}/abuse-reports/{report_id}/mitigations/appeal

**Resource:** [tseng-abuse-complaint-processor_other](../resources/tseng-abuse-complaint-processor-other.md)
**Request review on mitigations**
**Operation ID:** `RequestReview`

Request a review for mitigations on an account.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | string | Yes | Cloudflare Account ID |
| `report_id` | path | string | Yes | Abuse Report ID |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [abuse-reports_MitigationAppealRequest](../schemas/abuse-reports/abuse-reports-MitigationAppealRequest.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Mitigation appeals received |
| 500 | Failed to request review on delayed action. |

**Success Response Schema:**

[abuse-reports_MitigationAppealResult](../schemas/abuse-reports/abuse-reports-MitigationAppealResult.md)

## Security

- **api_token**
