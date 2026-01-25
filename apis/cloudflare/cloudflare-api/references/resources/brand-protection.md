# brand_protection

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/accounts/{account_id}/brand-protection/alerts` | Read all alerts on submitted domains | [View](../operations/get-accounts-account-id-brand-protection-alerts.md) |
| PATCH | `/accounts/{account_id}/brand-protection/alerts` | Update alerts on submitted domains by ID | [View](../operations/patch-accounts-account-id-brand-protection-alerts.md) |
| PATCH | `/accounts/{account_id}/brand-protection/alerts/clear` | Update verification statuses of tracked URLs to awaiting by ID | [View](../operations/patch-accounts-account-id-brand-protection-alerts-clear.md) |
| PATCH | `/accounts/{account_id}/brand-protection/alerts/refute` | Update verification statuses of tracked URLs to disproven by ID | [View](../operations/patch-accounts-account-id-brand-protection-alerts-refute.md) |
| PATCH | `/accounts/{account_id}/brand-protection/alerts/verify` | Update verification statuses of tracked URLs to confirmed by ID | [View](../operations/patch-accounts-account-id-brand-protection-alerts-verify.md) |
| GET | `/accounts/{account_id}/brand-protection/brands` | Read all brands | [View](../operations/get-accounts-account-id-brand-protection-brands.md) |
| POST | `/accounts/{account_id}/brand-protection/brands` | Create new brands | [View](../operations/post-accounts-account-id-brand-protection-brands.md) |
| DELETE | `/accounts/{account_id}/brand-protection/brands` | Delete brands by ID | [View](../operations/delete-accounts-account-id-brand-protection-brands.md) |
| GET | `/accounts/{account_id}/brand-protection/brands/patterns` | Read patterns for brands by ID | [View](../operations/get-accounts-account-id-brand-protection-brands-patterns.md) |
| POST | `/accounts/{account_id}/brand-protection/brands/patterns` | Create new patterns for brands by ID | [View](../operations/post-accounts-account-id-brand-protection-brands-patterns.md) |
| DELETE | `/accounts/{account_id}/brand-protection/brands/patterns` | Delete patterns for brands by ID | [View](../operations/delete-accounts-account-id-brand-protection-brands-patterns.md) |
| PATCH | `/accounts/{account_id}/brand-protection/clear` | Update verification statuses of submitted URLs to awaiting by ID | [View](../operations/patch-accounts-account-id-brand-protection-clear.md) |
| GET | `/accounts/{account_id}/brand-protection/domain-info` | Read submitted domains by ID | [View](../operations/get-accounts-account-id-brand-protection-domain-info.md) |
| GET | `/accounts/{account_id}/brand-protection/recent-submissions` | Read recent URL submissions | [View](../operations/get-accounts-account-id-brand-protection-recent-submissions.md) |
| PATCH | `/accounts/{account_id}/brand-protection/refute` | Update verification statuses of submitted URLs to disproven by ID | [View](../operations/patch-accounts-account-id-brand-protection-refute.md) |
| GET | `/accounts/{account_id}/brand-protection/submission-info` | Read URL submissions by ID | [View](../operations/get-accounts-account-id-brand-protection-submission-info.md) |
| POST | `/accounts/{account_id}/brand-protection/submit` | Create new URL submissions | [View](../operations/post-accounts-account-id-brand-protection-submit.md) |
| GET | `/accounts/{account_id}/brand-protection/tracked-domains` | Read submitted domains by pattern | [View](../operations/get-accounts-account-id-brand-protection-tracked-domains.md) |
| GET | `/accounts/{account_id}/brand-protection/url-info` | Read submitted URLs by ID | [View](../operations/get-accounts-account-id-brand-protection-url-info.md) |
| PATCH | `/accounts/{account_id}/brand-protection/verify` | Update verification statuses of submitted URLs to confirmed by ID | [View](../operations/patch-accounts-account-id-brand-protection-verify.md) |
| POST | `/internal/submit` | Internal route for testing URL submissions | [View](../operations/post-internal-submit.md) |
| GET | `/live` | Run liveness checks | [View](../operations/get-live.md) |
| GET | `/ready` | Run readiness checks | [View](../operations/get-ready.md) |
