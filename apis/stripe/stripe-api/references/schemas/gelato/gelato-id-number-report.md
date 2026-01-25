# gelato_id_number_report

Result from an id_number check

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `dob` | any | No | Date of birth. |
| `error` | any | No | Details on the verification error. Present when status is `unverified`. |
| `first_name` | string | No | First name. |
| `id_number` | string | No | ID number. When `id_number_type` is `us_ssn`, only the last 4 digits are present. |
| `id_number_type` | enum: br_cpf, sg_nric, us_ssn | No | Type of ID number. |
| `last_name` | string | No | Last name. |
| `status` | enum: unverified, verified | Yes | Status of this `id_number` check. |

