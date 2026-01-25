# code-scanning-default-setup-update

Configuration for code scanning default setup.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `state` | enum: configured, not-configured | No | The desired state of code scanning default setup. |
| `runner_type` | enum: standard, labeled | No | Runner type to be used. |
| `runner_label` | string | No | Runner label to be used if the runner type is labeled. |
| `query_suite` | enum: default, extended | No | CodeQL query suite to be used. |
| `threat_model` | enum: remote, remote_and_local | No | Threat model to be used for code scanning analysis. Use `remote` to analyze only network sources and `remote_and_local` to include local sources like filesystem access, command-line arguments, database reads, environment variable and standard input. |
| `languages` | string[] | No | CodeQL languages to be analyzed. |

