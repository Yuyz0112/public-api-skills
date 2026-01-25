# snapshot

Create a new snapshot of a repository's dependencies.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `version` | integer | Yes | The version of the repository snapshot submission. |
| `job` | object | Yes |  |
| `sha` | string | Yes | The commit SHA associated with this dependency snapshot. Maximum length: 40 characters. |
| `ref` | string | Yes | The repository branch that triggered this snapshot. |
| `detector` | object | Yes | A description of the detector used. |
| `metadata` | [metadata](metadata.md) | No |  |
| `manifests` | object | No | A collection of package manifests, which are a collection of related dependencies declared in a file or representing a logical group of dependencies. |
| `scanned` | string (date-time) | Yes | The time at which the snapshot was scanned. |

## Nested Fields

### `job`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | string | Yes | The external ID of the job. |
| `correlator` | string | Yes | Correlator provides a key that is used to group snapshots submitted over time. Only the "latest" submitted snapshot for a given combination of `job.correlator` and `detector.name` will be considered when calculating a repository's current dependencies. Correlator should be as unique as it takes to distinguish all detection runs for a given "wave" of CI workflow you run. If you're using GitHub Actions, a good default value for this could be the environment variables GITHUB_WORKFLOW and GITHUB_JOB concatenated together. If you're using a build matrix, then you'll also need to add additional key(s) to distinguish between each submission inside a matrix variation. |
| `html_url` | string | No | The url for the job. |

### `detector`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `name` | string | Yes | The name of the detector used. |
| `version` | string | Yes | The version of the detector used. |
| `url` | string | Yes | The url of the detector used. |

