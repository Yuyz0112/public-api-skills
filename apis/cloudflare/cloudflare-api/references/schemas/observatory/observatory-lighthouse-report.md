# observatory_lighthouse_report

The Lighthouse report.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `cls` | number | No | Cumulative Layout Shift. |
| `deviceType` | [observatory_device_type](observatory-device-type.md) | No |  |
| `error` | object | No |  |
| `fcp` | number | No | First Contentful Paint. |
| `jsonReportUrl` | string | No | The URL to the full Lighthouse JSON report. |
| `lcp` | number | No | Largest Contentful Paint. |
| `performanceScore` | number | No | The Lighthouse performance score. |
| `si` | number | No | Speed Index. |
| `state` | [observatory_lighthouse_state](observatory-lighthouse-state.md) | No |  |
| `tbt` | number | No | Total Blocking Time. |
| `ttfb` | number | No | Time To First Byte. |
| `tti` | number | No | Time To Interactive. |

## Nested Fields

### `error`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `code` | [observatory_lighthouse_error_code](observatory-lighthouse-error-code.md) | No |  |
| `detail` | string | No | Detailed error message. |
| `finalDisplayedUrl` | string | No | The final URL displayed to the user. |

