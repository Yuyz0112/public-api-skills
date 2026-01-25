# Zero Trust Risk Scoring

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/accounts/{account_id}/zt_risk_scoring/behaviors` | Get all behaviors and associated configuration | [View](../operations/dlp-risk-score-behaviors-get.md) |
| PUT | `/accounts/{account_id}/zt_risk_scoring/behaviors` | Update configuration for risk behaviors | [View](../operations/dlp-risk-score-behaviors-put.md) |
| GET | `/accounts/{account_id}/zt_risk_scoring/summary` | Get risk score info for all users in the account | [View](../operations/dlp-risk-score-summary-get.md) |
| GET | `/accounts/{account_id}/zt_risk_scoring/{user_id}` | Get risk event/score information for a specific user | [View](../operations/dlp-risk-score-summary-get-for-user.md) |
| POST | `/accounts/{account_id}/zt_risk_scoring/{user_id}/reset` | Clear the risk score for a particular user | [View](../operations/dlp-risk-score-reset-post.md) |
