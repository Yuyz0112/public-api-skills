# workers_assets

Configuration for assets within a Worker.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `config` | object | No | Configuration for assets within a Worker. |
| `jwt` | string | No | Token provided upon successful upload of all files from a registered manifest. |

## Nested Fields

### `config`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `_headers` | string | No | The contents of a _headers file (used to attach custom headers on asset responses). |
| `_redirects` | string | No | The contents of a _redirects file (used to apply redirects or proxy paths ahead of asset serving). |
| `html_handling` | enum: auto-trailing-slash, force-trailing-slash, drop-trailing-slash... | No | Determines the redirects and rewrites of requests for HTML content. |
| `not_found_handling` | enum: none, 404-page, single-page-application | No | Determines the response when a request does not match a static asset, and there is no Worker script. |
| `run_worker_first` | any | No |  |
| `serve_directly` | boolean | No | When true and the incoming request matches an asset, that will be served instead of invoking the Worker script. When false, requests will always invoke the Worker script. |

