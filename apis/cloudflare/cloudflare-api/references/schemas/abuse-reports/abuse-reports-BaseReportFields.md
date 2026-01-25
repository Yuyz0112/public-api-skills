# abuse-reports_BaseReportFields

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `act` | [abuse-reports_SubmissionReportType](abuse-reports-SubmissionReportType.md) | Yes |  |
| `comments` | string | No | Any additional comments about the infringement not exceeding 2000 characters |
| `company` | string | No | Text not exceeding 100 characters. This field may be released by Cloudflare to third parties such as the Lumen Database (https://lumendatabase.org/). |
| `email` | string | Yes | A valid email of the abuse reporter. This field may be released by Cloudflare to third parties such as the Lumen Database (https://lumendatabase.org/). |
| `email2` | string | Yes | Should match the value provided in `email` |
| `name` | string | Yes | Text not exceeding 255 characters. This field may be released by Cloudflare to third parties such as the Lumen Database (https://lumendatabase.org/). |
| `reported_country` | string | No | Text containing 2 characters |
| `reported_user_agent` | string | No | Text not exceeding 255 characters |
| `tele` | string | No | Text not exceeding 20 characters. This field may be released by Cloudflare to third parties such as the Lumen Database (https://lumendatabase.org/). |
| `title` | string | No | Text not exceeding 255 characters |
| `urls` | string | Yes | A list of valid URLs separated by ‘\n’ (new line character). The list of the URLs should not exceed 250 URLs. All URLs should have the same hostname. Each URL should be unique. This field may be released by Cloudflare to third parties such as the Lumen Database (https://lumendatabase.org/). |

