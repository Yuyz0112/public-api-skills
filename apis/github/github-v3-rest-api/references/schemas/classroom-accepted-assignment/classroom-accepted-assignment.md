# classroom-accepted-assignment

A GitHub Classroom accepted assignment

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | integer | Yes | Unique identifier of the repository. |
| `submitted` | boolean | Yes | Whether an accepted assignment has been submitted. |
| `passing` | boolean | Yes | Whether a submission passed. |
| `commit_count` | integer | Yes | Count of student commits. |
| `grade` | string | Yes | Most recent grade. |
| `students` | simple-classroom-user[] | Yes |  |
| `repository` | [simple-classroom-repository](simple-classroom-repository.md) | Yes |  |
| `assignment` | [simple-classroom-assignment](simple-classroom-assignment.md) | Yes |  |

