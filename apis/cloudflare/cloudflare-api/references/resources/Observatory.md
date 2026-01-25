# Observatory

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/zones/{zone_id}/speed_api/availabilities` | Get quota and availability | [View](../operations/speed-get-availabilities.md) |
| GET | `/zones/{zone_id}/speed_api/pages` | List tested webpages | [View](../operations/speed-list-pages.md) |
| GET | `/zones/{zone_id}/speed_api/pages/{url}/tests` | List page test history | [View](../operations/speed-list-test-history.md) |
| POST | `/zones/{zone_id}/speed_api/pages/{url}/tests` | Start page test | [View](../operations/speed-create-test.md) |
| DELETE | `/zones/{zone_id}/speed_api/pages/{url}/tests` | Delete all page tests | [View](../operations/speed-delete-tests.md) |
| GET | `/zones/{zone_id}/speed_api/pages/{url}/tests/{test_id}` | Get a page test result | [View](../operations/speed-get-test.md) |
| GET | `/zones/{zone_id}/speed_api/pages/{url}/trend` | List core web vital metrics trend | [View](../operations/speed-list-page-trend.md) |
| GET | `/zones/{zone_id}/speed_api/schedule/{url}` | Get a page test schedule | [View](../operations/speed-get-scheduled-test.md) |
| POST | `/zones/{zone_id}/speed_api/schedule/{url}` | Create scheduled page test | [View](../operations/speed-create-scheduled-test.md) |
| DELETE | `/zones/{zone_id}/speed_api/schedule/{url}` | Delete scheduled page test | [View](../operations/speed-delete-test-schedule.md) |
