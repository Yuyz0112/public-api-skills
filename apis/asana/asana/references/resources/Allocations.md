# Allocations

An allocation object represents how much of a resource (e.g. person, team) is dedicated to a specific work object (e.g. project, portfolio) over a specific period of time. The effort value of an allocation object can be a percentage or number of hours.

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/allocations/{allocation_gid}` | Get an allocation | [View](../operations/getAllocation.md) |
| PUT | `/allocations/{allocation_gid}` | Update an allocation | [View](../operations/updateAllocation.md) |
| DELETE | `/allocations/{allocation_gid}` | Delete an allocation | [View](../operations/deleteAllocation.md) |
| GET | `/allocations` | Get multiple allocations | [View](../operations/getAllocations.md) |
| POST | `/allocations` | Create an allocation | [View](../operations/createAllocation.md) |
