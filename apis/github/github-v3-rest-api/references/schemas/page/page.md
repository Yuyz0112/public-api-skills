# page

The configuration for GitHub Pages for a repository.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `url` | string (uri) | Yes | The API address for accessing this Page resource. |
| `status` | enum: built, building, errored | Yes | The status of the most recent build of the Page. |
| `cname` | string | Yes | The Pages site's custom domain |
| `protected_domain_state` | enum: pending, verified, unverified | No | The state if the domain is verified |
| `pending_domain_unverified_at` | string (date-time) | No | The timestamp when a pending domain becomes unverified. |
| `custom_404` | boolean | Yes | Whether the Page has a custom 404 page. |
| `html_url` | string (uri) | No | The web address the Page can be accessed from. |
| `build_type` | enum: legacy, workflow | No | The process in which the Page will be built. |
| `source` | [pages-source-hash](pages-source-hash.md) | No |  |
| `public` | boolean | Yes | Whether the GitHub Pages site is publicly visible. If set to `true`, the site is accessible to anyone on the internet. If set to `false`, the site will only be accessible to users who have at least `read` access to the repository that published the site. |
| `https_certificate` | [pages-https-certificate](pages-https-certificate.md) | No |  |
| `https_enforced` | boolean | No | Whether https is enabled on the domain |

