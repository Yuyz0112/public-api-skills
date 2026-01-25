# cc_CustomResourceAllocation

Custom resource allocation with explicit vcpu, memory, and disk. Custom resource allocations must adhere to the following limits:
- At least 1 vCPU
- At least 3 GiB memory for each vCPU
- Disk GB can be at most 2x memory in GiB


**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `disk_mb` | integer | Yes | The disk size in MB. |
| `memory_mib` | integer | Yes | Specify the memory to be used for the deployment, in MiB. The default will be the one configured for the account. |
| `vcpu` | number (float) | Yes | Specify the vcpu to be used for the deployment. Vcpu must be at least 1. The input value will be rounded to
the nearest 0.0001. The default will be the one configured for the account.
 |

