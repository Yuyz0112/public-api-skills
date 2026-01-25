# AutomationActionsScriptActionDataReference

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `script` | string | Yes | Body of the script to be executed on the Runner. To execute it, the Runner will write the content of the property into a temp file, make the file executable and execute it. It is assumed that the Runner has a properly configured environment to run the script as an executable file. This behaviour can be altered by providing the `invocation_command` property. The maxLength value is specified in bytes. |
| `invocation_command` | string | No | The command to executed a script with. With the body of the script written into a temp file, the Runner will execute the `<invocation_command> <temp_file>` command. The maxLength value is specified in bytes. |

