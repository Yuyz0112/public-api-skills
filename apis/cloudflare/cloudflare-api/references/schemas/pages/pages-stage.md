# pages_stage

The status of the deployment.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `ended_on` | string (date-time) | Yes | When the stage ended. |
| `name` | enum: queued, initialize, clone_repo... | Yes | The current build stage. |
| `started_on` | string (date-time) | Yes | When the stage started. |
| `status` | enum: success, idle, active... | Yes | State of the current stage. |

