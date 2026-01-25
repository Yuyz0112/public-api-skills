# pages_build_config

Configs for the project build process.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `build_caching` | boolean | No | Enable build caching for the project. |
| `build_command` | string | No | Command used to build project. |
| `destination_dir` | string | No | Assets output directory of the build. |
| `root_dir` | string | No | Directory to run the command. |
| `web_analytics_tag` | string | Yes | The classifying tag for analytics. |
| `web_analytics_token` | string | Yes | The auth token for analytics. |

