# DEX Remote Commands

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/accounts/{account_id}/dex/commands` | List account commands | [View](../operations/get-commands.md) |
| POST | `/accounts/{account_id}/dex/commands` | Create account commands | [View](../operations/post-commands.md) |
| GET | `/accounts/{account_id}/dex/commands/devices` | List devices eligible for remote captures | [View](../operations/get-commands-eligible-devices.md) |
| GET | `/accounts/{account_id}/dex/commands/quota` | Returns account commands usage, quota, and reset time | [View](../operations/get-commands-quota.md) |
| GET | `/accounts/{account_id}/dex/commands/{command_id}/downloads/{filename}` | Download command output file | [View](../operations/get-commands-command-id-downloads-filename.md) |
