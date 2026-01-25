# Sections

A section is a subdivision of a project that groups tasks together. It can either be a header above a list of tasks in a list view or a column in a board view of a project.

Sections are largely a shared idiom in Asana’s API for both list and board views of a project regardless of the project’s layout.

The ‘memberships’ property when [getting a task](/reference/gettask) will return the information for the section or the column under ‘section’ in the response.

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/sections/{section_gid}` | Get a section | [View](../operations/getSection.md) |
| PUT | `/sections/{section_gid}` | Update a section | [View](../operations/updateSection.md) |
| DELETE | `/sections/{section_gid}` | Delete a section | [View](../operations/deleteSection.md) |
| GET | `/projects/{project_gid}/sections` | Get sections in a project | [View](../operations/getSectionsForProject.md) |
| POST | `/projects/{project_gid}/sections` | Create a section in a project | [View](../operations/createSectionForProject.md) |
| POST | `/sections/{section_gid}/addTask` | Add task to section | [View](../operations/addTaskForSection.md) |
| POST | `/projects/{project_gid}/sections/insert` | Move or Insert sections | [View](../operations/insertSectionForProject.md) |
