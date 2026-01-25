# api-overview

Api Overview

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `verifiable_password_authentication` | boolean | Yes |  |
| `ssh_key_fingerprints` | object | No |  |
| `ssh_keys` | string[] | No |  |
| `hooks` | string[] | No |  |
| `github_enterprise_importer` | string[] | No |  |
| `web` | string[] | No |  |
| `api` | string[] | No |  |
| `git` | string[] | No |  |
| `packages` | string[] | No |  |
| `pages` | string[] | No |  |
| `importer` | string[] | No |  |
| `actions` | string[] | No |  |
| `actions_macos` | string[] | No |  |
| `codespaces` | string[] | No |  |
| `dependabot` | string[] | No |  |
| `copilot` | string[] | No |  |
| `domains` | object | No |  |

## Nested Fields

### `ssh_key_fingerprints`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `SHA256_RSA` | string | No |  |
| `SHA256_DSA` | string | No |  |
| `SHA256_ECDSA` | string | No |  |
| `SHA256_ED25519` | string | No |  |

### `domains`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `website` | string[] | No |  |
| `codespaces` | string[] | No |  |
| `copilot` | string[] | No |  |
| `packages` | string[] | No |  |
| `actions` | string[] | No |  |
| `actions_inbound` | object | No |  |
| `artifact_attestations` | object | No |  |

#### `domains.actions_inbound`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `full_domains` | string[] | No |  |
| `wildcard_domains` | string[] | No |  |

#### `domains.artifact_attestations`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `trust_domain` | string | No |  |
| `services` | string[] | No |  |

