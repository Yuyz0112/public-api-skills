# classroom-assignment-grade

Grade for a student or groups GitHub Classroom assignment

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `assignment_name` | string | Yes | Name of the assignment |
| `assignment_url` | string | Yes | URL of the assignment |
| `starter_code_url` | string | Yes | URL of the starter code for the assignment |
| `github_username` | string | Yes | GitHub username of the student |
| `roster_identifier` | string | Yes | Roster identifier of the student |
| `student_repository_name` | string | Yes | Name of the student's assignment repository |
| `student_repository_url` | string | Yes | URL of the student's assignment repository |
| `submission_timestamp` | string | Yes | Timestamp of the student's assignment submission |
| `points_awarded` | integer | Yes | Number of points awarded to the student |
| `points_available` | integer | Yes | Number of points available for the assignment |
| `group_name` | string | No | If a group assignment, name of the group the student is in |

