# Email Security

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/accounts/{account_id}/email-security/investigate` | Search email messages | [View](../operations/email-security-investigate.md) |
| POST | `/accounts/{account_id}/email-security/investigate/move` | Move multiple messages | [View](../operations/email-security-post-bulk-message-move.md) |
| POST | `/accounts/{account_id}/email-security/investigate/preview` | Preview for non-detection messages | [View](../operations/email-security-post-preview.md) |
| POST | `/accounts/{account_id}/email-security/investigate/release` | Release messages from quarantine | [View](../operations/email-security-post-release.md) |
| GET | `/accounts/{account_id}/email-security/investigate/{postfix_id}` | Get message details | [View](../operations/email-security-get-message.md) |
| GET | `/accounts/{account_id}/email-security/investigate/{postfix_id}/detections` | Get message detection details | [View](../operations/email-security-get-message-detections.md) |
| POST | `/accounts/{account_id}/email-security/investigate/{postfix_id}/move` | Move a message | [View](../operations/email-security-post-message-move.md) |
| GET | `/accounts/{account_id}/email-security/investigate/{postfix_id}/preview` | Get email preview | [View](../operations/email-security-get-message-preview.md) |
| GET | `/accounts/{account_id}/email-security/investigate/{postfix_id}/raw` | Get raw email content | [View](../operations/email-security-get-message-raw.md) |
| POST | `/accounts/{account_id}/email-security/investigate/{postfix_id}/reclassify` | Change email classfication | [View](../operations/email-security-post-reclassify.md) |
| GET | `/accounts/{account_id}/email-security/investigate/{postfix_id}/trace` | Get email trace | [View](../operations/email-security-get-message-trace.md) |
| GET | `/accounts/{account_id}/email-security/phishguard/reports` | Get `PhishGuard` reports | [View](../operations/email-security-get-phishguard-reports.md) |
| GET | `/accounts/{account_id}/email-security/submissions` | Get reclassify submissions | [View](../operations/email-security-submissions.md) |
