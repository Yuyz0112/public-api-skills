# Content Scanning

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| POST | `/zones/{zone_id}/content-upload-scan/disable` | Disable Content Scanning | [View](../operations/waf-content-scanning-disable.md) |
| POST | `/zones/{zone_id}/content-upload-scan/enable` | Enable Content Scanning | [View](../operations/waf-content-scanning-enable.md) |
| GET | `/zones/{zone_id}/content-upload-scan/payloads` | List Existing Custom Scan Expressions | [View](../operations/waf-content-scanning-list-custom-scan-expressions.md) |
| POST | `/zones/{zone_id}/content-upload-scan/payloads` | Add Custom Scan Expressions | [View](../operations/waf-content-scanning-add-custom-scan-expressions.md) |
| DELETE | `/zones/{zone_id}/content-upload-scan/payloads/{expression_id}` | Delete a Custom Scan Expression | [View](../operations/waf-content-scanning-delete-custom-scan-expressions.md) |
| GET | `/zones/{zone_id}/content-upload-scan/settings` | Get Content Scanning Status | [View](../operations/waf-content-scanning-get-status.md) |
| PUT | `/zones/{zone_id}/content-upload-scan/settings` | Update Content Scanning Status | [View](../operations/waf-content-scanning-update-settings.md) |
