# tseng-abuse-complaint-processor_other

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/accounts/{account_id}/abuse-reports` | List abuse reports | [View](../operations/ListAbuseReports.md) |
| GET | `/accounts/{account_id}/abuse-reports/{report_id}/mitigations` | List abuse report mitigations | [View](../operations/ListMitigations.md) |
| POST | `/accounts/{account_id}/abuse-reports/{report_id}/mitigations/appeal` | Request review on mitigations | [View](../operations/RequestReview.md) |
| GET | `/accounts/{account_id}/abuse-reports/{report_param}` | Abuse Report Details | [View](../operations/GetAbuseReport.md) |
| POST | `/accounts/{account_id}/abuse-reports/{report_param}` | Submit an abuse report | [View](../operations/SubmitAbuseReport.md) |
